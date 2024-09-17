# Sentiment Analysis on IMDB Movie Reviews

This project performs sentiment analysis on IMDB movie reviews using machine learning. The goal is to classify reviews as either positive or negative based on their content.

- **Dataset**: IMDB movie reviews dataset, which contains movie reviews labelled with sentiments (positive or negative).
  
- **Preprocessing**: 
  - Conversion of text to lowercase.
  - Remove HTML tags, URLs, special characters, and stopwords.
  - Tokenization and stemming of words.
    
- **Feature Extraction**: Utilized 'TfidfVectorizer' to convert text data into numerical features for model training.
  
- **Model Selection**: 
  - Implemented and evaluated three machine learning models: Logistic Regression, Naive Bayes, and Support Vector Classification (SVC).
  - SVC was chosen as the final model after comparison due to its superior performance.
    
- **Model Evaluation**: 
  - Evaluated the models using accuracy, confusion matrix, and classification report metrics.
  - Compared predictions with actual values through the confusion matrix.
