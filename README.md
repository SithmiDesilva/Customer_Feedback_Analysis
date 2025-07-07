# Customer Feedback Analysis & Sentiment Classification

## Overview

This project analyzes customer support tickets to uncover insights about customer satisfaction, sentiment trends, and common issues. Using Natural Language Processing (NLP) and machine learning techniques, we preprocess textual feedback, perform sentiment analysis, topic modeling, and build predictive models to classify customer satisfaction.

---

## Key Features

- **Data Exploration & Cleaning:**  
  Visualize distributions, handle missing data, and preprocess text by cleaning, lemmatizing, and removing stopwords.

- **Sentiment Analysis:**  
  Apply VADER sentiment analyzer to assign sentiment scores and labels to customer feedback.

- **Feature Engineering:**  
  Combine TF-IDF text vectors, structured ticket metadata (priority, type), and sentiment scores.

- **Handling Imbalanced Data:**  
  Use SMOTE oversampling technique to balance the dataset for robust model training.

- **Machine Learning Models:**  
  Tune and compare Random Forest and LightGBM classifiers with hyperparameter optimization.

- **Model Evaluation:**  
  Visualize performance through accuracy, classification reports, confusion matrices, ROC and Precision-Recall curves.

- **Topic Modeling:**  
  Use Latent Dirichlet Allocation (LDA) to extract and label dominant feedback topics, aiding deeper understanding.

- **Keyword Trend Analysis:**  
  Identify and visualize the most frequent keywords overall, and separately for positive and negative feedback.

---

## Project Structure

- **Data:**  
  `customer_support_tickets.csv` – Contains raw customer ticket data.

- **Notebooks / Scripts:**  
  - Data loading and exploratory data analysis (EDA)  
  - Text preprocessing and sentiment analysis  
  - Feature engineering and model training  
  - Topic modeling and visualization

- **Visualizations:**  
  Histograms, boxplots, correlation heatmaps, confusion matrices, ROC/PR curves, keyword bar charts.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-feedback-analysis.git
   cd customer-feedback-analysis
