# Book Recommendation System

The Book Recommendation System is a project that utilizes the count vectorizer and cosine similarity techniques to provide book recommendations based on various features such as Book-Author, Book-Title, and Publisher. This system aims to help users discover new books that align with their preferences.

## Features

The main features of the book recommendation system include:

1. **Book-Author**: The system takes into account the author of the book to recommend similar books by the same author or authors with similar writing styles.

2. **Book-Title**: The system considers the title of the book to recommend similar books with related themes or genres.

3. **Publisher**: The system takes the publisher into account to recommend books from the same publisher or publishers with similar publishing styles.

## How It Works

The book recommendation system follows these steps to provide recommendations:

1. **Data Preprocessing**: The system preprocesses the book dataset by cleaning and transforming the data into a suitable format for analysis.

2. **Feature Extraction**: Using the count vectorizer technique, the system converts the text-based features (Book-Author, Book-Title, Publisher) into numerical representations, considering the frequency of words in each feature.

3. **Cosine Similarity**: The system calculates the cosine similarity between the feature vectors of each book to determine the closeness between books based on their features.

4. **Recommendation Generation**: Given a target book, the system identifies similar books based on their cosine similarity scores. It then generates a list of recommended books that are most similar to the target book.

## Usage

To use the book recommendation system:

1. Data: Prepare a dataset containing book information, including Book-Author, Book-Title, Publisher.

2. Data Preprocessing: Clean and preprocess the dataset, handling missing values, removing duplicates, and performing any necessary transformations.

3. Model Training: Apply the count vectorizer technique to convert the text-based features into numerical representations. Then, calculate the cosine similarity matrix using the feature vectors.

4. Recommendation: Given a target book, input its features into the system. The system will provide a list of recommended books based on the calculated cosine similarity scores.

## Dependencies

The following dependencies are required to run the book recommendation system:
  
- Pandas 
- Scikit-learn 

## References

Tutorial by Natassha Selvaraj in https://365datascience.com/.

