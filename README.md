# Fake News Detection App

## Overview

This project is a Machine Learning-based Fake News Detection System that classifies news articles as either Real News or Fake News.

The application uses Natural Language Processing (NLP) techniques and a Logistic Regression model trained on a labeled news dataset. Users can enter news content through a Streamlit web interface and instantly receive a prediction.

## Features

* Detects Real and Fake News
* User-friendly Streamlit interface
* Machine Learning-based classification
* TF-IDF text vectorization
* Instant predictions
* Deployed on Streamlit Cloud

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Pickle

### Machine Learning

* Logistic Regression
* TF-IDF Vectorization

---

## Dataset

The model was trained using:

* Fake.csv
* True.csv

The dataset contains thousands of real and fake news articles used for supervised machine learning classification.

## Project Workflow

### 1. Data Collection

Loaded Fake.csv and True.csv datasets.

### 2. Data Preprocessing

* Combined datasets
* Assigned labels
* Removed unnecessary columns
* Cleaned text data

### 3. Feature Engineering

Used TF-IDF Vectorizer to convert text into numerical features.

### 4. Model Training

Trained a Logistic Regression classifier on the processed data.

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 6. Model Saving

Saved:

* fake_news_model.pkl
* vectorizer.pkl

### 7. Deployment

Created a Streamlit web application and deployed it using Streamlit Cloud.

## Project Structure

fake-news-detection/

├── app.py

├── fake_news_model.pkl

├── vectorizer.pkl

├── requirements.txt

├── News_Detection.ipynb

└── README.md

## How to Run Locally

1. Clone the repository

git clone <repository-url>

2. Install dependencies

pip install -r requirements.txt

3. Run the application

streamlit run app.py

## Model Performance

Logistic Regression achieved approximately 99% accuracy on the test dataset.

Note:
Real-world performance may vary depending on the quality and length of the news article provided by the user.

## Future Improvements

* Use Passive Aggressive Classifier
* Use Linear SVM
* Improve text preprocessing
* Add confidence scores
* Add probability visualization charts
* Use advanced NLP models such as BERT
* Improve UI design

## Author

Sushmita Poddar

Aspiring Data Scientist | Machine Learning Enthusiast

## Deployment

The application is deployed on Streamlit Cloud and can be accessed through the public Streamlit URL.
Here is the link- https://fake-news-detection-893dbnmoiqwloxcxjnowge.streamlit.app/
