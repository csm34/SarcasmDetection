# Sarcasm Detection Project

This project is a machine learning-based sarcasm detection application. The goal is to classify news headlines as either "Sarcasm" or "Not Sarcasm" using natural language processing techniques and a Naive Bayes classifier.


## Features

- Dataset Handling: Automatically downloads the Sarcasm Detection Dataset from Kaggle using the `kagglehub` library.
- Exploratory Data Analysis (EDA): Includes visualizations of label distributions and word clouds.
- Preprocessing: Vectorizes text data using `CountVectorizer` from Scikit-learn.
- Model Training and Evaluation: Implements and evaluates a Naive Bayes classifier.
- Visualization: Creates confusion matrices and feature importance graphs for better insights.
- Interactive Prediction: Accepts user input to classify custom headlines as sarcastic or not.


## Code Overview
1. Dataset Loading
Automatically downloads and extracts the dataset using kagglehub.
Loads the JSON file into a Pandas DataFrame for processing.
2. Exploratory Data Analysis (EDA)
Label Distribution: Visualized using a bar chart.
Word Cloud: Displays the most frequent words in the dataset headlines.
3. Data Preprocessing
Converts headlines into numerical features using CountVectorizer.
Splits the data into training and testing sets.
4. Model Training and Evaluation
Trains a Bernoulli Naive Bayes classifier on the processed data.
Evaluates the model using accuracy, classification reports, and confusion matrices.
5. User Interaction
Allows the user to input a custom headline and predicts whether it is sarcastic or not.


## License
This project is licensed under the MIT License.
