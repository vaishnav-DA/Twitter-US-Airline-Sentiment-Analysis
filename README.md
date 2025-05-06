# Twitter US Airline Sentiment Analysis

## Project Overview
This project analyzes the sentiment of tweets related to US airlines. The goal is to predict whether a tweet expresses a **positive** or **negative/neutral** sentiment based on the text content.

## Dataset
The dataset used in this project is the [**Twitter US Airline Sentiment** dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment). It contains 14,000 tweets labeled with sentiments, where the target variable is the sentiment of the tweet: **positive**, **negative**, or **neutral**.

## Key Steps Involved:
1. **Data Cleaning and Preprocessing**
   - Removing unnecessary columns
   - Handling missing values
   - Converting sentiments to binary (Positive = 1, Negative/Neutral = 0)

2. **Text Vectorization**
   - Using CountVectorizer to transform text into numerical features (bag-of-words model)
   - Optionally, using TF-IDF Vectorizer for better feature representation

3. **Model Training**
   - Training a Naive Bayes classifier to classify sentiment as positive or negative/neutral
   - Hyperparameter tuning using GridSearchCV to find the best model parameters

4. **Model Evaluation**
   - Evaluating the model using metrics such as accuracy, precision, recall, and F1-score
   - Visualizing model performance with a confusion matrix

## Libraries Used:
- **pandas**: for data manipulation
- **numpy**: for numerical operations
- **matplotlib**: for data visualization
- **seaborn**: for enhanced data visualization
- **sklearn**: for machine learning tasks (model training, evaluation, vectorization)
- **joblib**: for saving the trained model

## Instructions to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/vaishnav-DA/Twitter-US-Airline-Sentiment-Analysis.git
