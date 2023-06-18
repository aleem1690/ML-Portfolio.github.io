# Hate Detection Algorithm

The Hate Detection Algorithm is a project that aims to identify hate speech in text using a combination of count vectorization, decision trees, and text cleaning techniques. The algorithm is designed to classify text into different categories based on its level of hate speech.

## Features

The main features of the hate detection algorithm include:

1. Text Cleaning: Text cleaning operations are performed such as removing special characters, URLs, and numbers from the text data.

2. Stopword Removal: Stopwords, which are common words that do not contribute significantly to the classification task are removed. This step helps to eliminate noise from the text data.

3. Count Vectorization: Count vectorization converts text into numerical representations, considering the frequency of words in each document. This technique helps in transforming text data into a format suitable for machine learning algorithms.

4. Decision Tree Classifier: Decision tree classifier model is built to categorize text into different classes based on the extracted features and patterns. The decision tree algorithm uses a tree-like model of decisions and their possible consequences to make predictions.

## Usage

To use the hate detection algorithm:

1. Data: Prepare a dataset containing text samples and their corresponding target variables (hate speech classes).

2. Data Preprocessing: Clean and preprocess the text data by removing special characters, URLs, and numbers. This step helps in reducing noise and improving the quality of the input data.

3. Stopword Removal: Remove stopwords from the preprocessed text data. Stopwords are commonly occurring words (e.g., "the", "is", "and") that do not carry much meaning and can be safely ignored for classification purposes.

4. Feature Extraction: Apply count vectorization to convert the preprocessed text data into numerical representations. This step involves converting text data into a suitable format for training the decision tree classifier.

5. Model Training: Train a decision tree classifier on the vectorized data and the target variables. The decision tree learns patterns and relationships between the features (words) and the target variables (hate speech classes) during the training process.

6. Classification: Given a new text input, apply the same text cleaning and preprocessing techniques. Vectorize the preprocessed text and use the trained decision tree classifier to predict the appropriate hate speech class for the input.

## Dependencies

The following dependencies are required to run the hate detection algorithm:

- NumPy 
- Pandas 
- Scikit-learn
- NLTK
- re
- matplotlib
- seaborn
