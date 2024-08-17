# 🐦 Twitter Airline Sentiment Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.x-brightgreen.svg)](https://www.python.org/)

Welcome to the **Twitter Airline Sentiment Analysis** project! This project utilizes machine learning techniques to analyze and predict sentiments from tweets related to major U.S. airlines. The goal is to classify tweets as positive, neutral, or negative using various machine learning models and natural language processing (NLP) techniques.

![Sentiment Analysis](https://via.placeholder.com/800x300.png?text=Twitter+Airline+Sentiment+Analysis)

## 📝 Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Models Used](#models-used)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## 🚀 Introduction

Sentiment analysis, also known as opinion mining, is a significant tool for understanding public opinion, especially on platforms like Twitter. This project focuses on analyzing sentiments from tweets related to major U.S. airlines. By classifying tweets as positive, neutral, or negative, we can better understand public perception of different airlines and their services.

## 📊 Dataset

The dataset used in this project is the [Twitter Airline Sentiment dataset](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment). It contains tweets from February 2015, where contributors labeled each tweet as positive, neutral, or negative. The dataset also includes reasons for negative sentiments, such as "late flight" or "rude service."

## 🛠️ Methodology

The project follows these key steps:

1. **Data Collection**: The dataset was sourced from Kaggle.
2. **Data Analysis & Visualization**: Exploratory data analysis (EDA) was conducted to understand the distribution of sentiments.
3. **Data Preprocessing**: The text data was cleaned and preprocessed using techniques such as tokenization and vectorization (TF-IDF).
4. **Model Training**: Several machine learning models were trained on the preprocessed data.
5. **Model Evaluation**: The models were evaluated based on accuracy and other performance metrics.

## 🤖 Models Used

We implemented and compared the following machine learning models:

- **🔹 Logistic Regression**
- **🔹 Support Vector Machines (SVM)**
- **🔹 Random Forest Classifier**
- **🔹 Naive Bayes**
- **🔹 K-Nearest Neighbors (KNN)**
- **🔹 Decision Tree Classifier**
- **🔹 AdaBoost Classifier**

The **AdaBoost Classifier** showed the best performance with an accuracy of **79%**.

## 📈 Results

| Model                      | Accuracy |
| --------------------------- | -------- |
| Naive Bayes                 | 68%      |
| Logistic Regression         | 77%      |
| Support Vector Machines     | 78%      |
| Random Forest Classifier    | 76%      |
| K-Nearest Neighbors         | 59%      |
| Decision Tree Classifier    | 75%      |
| **AdaBoost Classifier**     | **79%**  |

The AdaBoost Classifier achieved the highest accuracy, while K-Nearest Neighbors had the lowest accuracy.

## 🛠️ Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/twitter-airline-sentiment.git
   cd twitter-airline-sentiment

🖥️ Usage
1. Run the Jupyter notebook to explore the workflow:
   ```bash
      jupyter notebook Twitter_sentiment_analysis.ipynb
   
2. Modify the notebook or script as needed for your analysis.

3. Explore the results through visualizations and compare model accuracy.

👥 Contributors
1. Shriniket Dixit 
2Raj Gupta 

📧 Contact
For any questions or issues, please reach out to 📬 dixitshriniket976@gmail.com.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
