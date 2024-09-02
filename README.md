# Hate-Speech-Classification-using-LSTM

This project involves the development of a Long Short-Term Memory (LSTM) network to classify text data as hate speech, abusive language, or neither. Leveraging advanced NLP techniques and LSTM networks, the model aims to accurately predict and identify harmful content on social platforms.

## Features

- **Data Preprocessing**: The text data undergoes extensive cleaning and preprocessing which includes tokenization and sequence padding to prepare it for the LSTM model.
- **LSTM Model**: The use of LSTM helps in capturing the contextual relationships within the text data which is crucial for accurately classifying tweets.
- **Performance Evaluation**: The model's performance is evaluated using accuracy metrics and a confusion matrix to ensure reliability in real-world scenarios.

## Prerequisites
The project requires the following dependencies:
Python 3.6+ \
TensorFlow 2.x \
Keras \
NumPy \
Matplotlib \
NLTK \
scikit-learn

## Model Architecture

The model comprises several layers including:
- Embedding layer for converting text into meaningful vectors 
- LSTM layer to capture dependencies in the text data
- Dense output layer with sigmoid activation to classify the text

## Results

The model achieves a high accuracy rate with detailed metrics available in the training logs. Here are key highlights:
- Test Accuracy: Over 92%
- Robust classification with detailed metrics available through confusion matrices and classification reports.

## Conclusion

This model demonstrates effective hate speech detection using LSTM, providing a strong foundation for further exploration and development in text-based classification tasks.
