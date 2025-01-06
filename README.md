# Fake News Detection Project
This project is designed to detect whether a given piece of news is fake or not by using various machine learning models. The system processes textual data and classifies it into two categories: Fake News or Not a Fake News. The project leverages different classification algorithms such as Logistic Regression, Decision Tree, Gradient Boosting, and Random Forest to predict the truthfulness of news articles.

## Key Features:
Data Preprocessing: The news articles undergo text preprocessing steps, such as tokenization, stopword removal, and stemming/lemmatization.
Text Vectorization: The news articles are converted into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
Multiple Classification Models: The system uses several machine learning models for classification:
Logistic Regression
Decision Tree
Gradient Boosting Classifier
Random Forest Classifier
Model Evaluation: The performance of each model is evaluated using metrics like accuracy, precision, recall, and F1-score.
Installation:
To run this project, you need to install the following libraries:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib
Additionally, you can install any other libraries if required.

## How to Run:
Prepare your data: You need to have a dataset with labeled news articles (Fake or Not Fake). The dataset must be in CSV format with at least two columns:

text: The content of the news article.
label: The label (0 for Fake, 1 for Not Fake).
Train the models: Use the provided code to train the machine learning models by fitting them to the training data.

Make Predictions: You can test the models with new, unseen news articles. Input the text of the news article, and the system will predict whether the news is fake or not.

Evaluate: Check the performance of the models with the evaluation metrics.

## Example Usage:
python
Copy code
# Example of testing the models with new news articles
news = input("Enter news article: ")
manual_testing(news)
Output:
The program will return predictions from all the models, e.g.,:

yaml
Copy code
LR Prediction: Not a Fake News 
DT Prediction: Fake News 
GBC Prediction: Not a Fake News 
RFC Prediction: Fake News
