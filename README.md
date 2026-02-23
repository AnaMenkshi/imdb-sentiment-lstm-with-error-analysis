## LSTM-Based Sentiment Analysis on IMDb Reviews

### Overview
This project presents an LSTM-based deep learning approach for binary sentiment analysis on the IMDb movie reviews dataset.
The objective is to classify reviews as positive or negative while evaluating model performance through accuracy metrics and detailed error analysis.
The proposed model achieves strong generalization and demonstrates competitive performance compared to recent related works.

#### Dataset
IMDB Dataset.csv
Contains labeled movie reviews used for training, validation, and testing. Reviews are preprocessed and tokenized before being passed to the model.

#### Project Structure

##### LSTM1.ipynb
Implements the full LSTM sentiment analysis pipeline, including data preprocessing, tokenization, model architecture, training, and evaluation.

##### LSTM2.ipynb
Provides an in-depth analysis of the dataset, model predictions, and error patterns, including false positives, false negatives, confidence-based errors, and review length analysis.

#### Methodology
Text preprocessing and tokenization with a fixed vocabulary size
Sequence padding and truncation for uniform input length
LSTM-based neural network for sentiment classification
Binary cross-entropy loss with accuracy-based evaluation
Detailed post-hoc error analysis to identify model limitations

#### Results
Training Accuracy: 93.40%
Validation Accuracy: 87.06%
The results indicate strong learning capability and good generalization performance, outperforming or matching comparable LSTM-based approaches reported in recent studies.

#### Key Findings
Long reviews did not significantly impact model performance
Subtle positive sentiment remains a moderate challenge
High-confidence errors primarily arise from sarcasm and negation, representing the main limitation of the model

#### Conclusion
The proposed LSTM model successfully captures sentiment patterns in IMDb reviews and demonstrates strong performance and robustness.
Compared to previous work, the model achieves improved accuracy and more detailed error characterization, highlighting its effectiveness and practical relevance.

#### Requirements
Python
NumPy
PyTorch / Keras (as used in the notebooks)
Google Colab (recommended for execution)

#### Usage
Upload the dataset to Google Colab
Run LSTM1.ipynb to train and evaluate the model
Run LSTM2.ipynb for extended analysis and error inspectionery step of the work done

#### Author
Ana Menkshi
