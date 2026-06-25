# Amazon Review Sentiment Analysis

## Project Overview

This project performs Sentiment Analysis on Amazon Product Reviews using Natural Language Processing (NLP) and Machine Learning techniques.

The objective is to classify reviews into Positive, Neutral, and Negative sentiments based on customer feedback.

---

## Dataset Information

- Dataset: Amazon Fine Food Reviews
- Total Reviews: 568,454
- Features: 10
- Sentiment Categories:
  - Positive
  - Neutral
  - Negative

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- NLTK
- Scikit-learn
- WordCloud

---

## Project Workflow

### 1. Data Loading
- Imported Amazon Reviews dataset
- Checked dataset structure and dimensions

### 2. Data Cleaning
- Removed special characters
- Converted text to lowercase
- Removed unnecessary spaces

### 3. Text Preprocessing
- Stopword removal using NLTK
- Text normalization

### 4. Exploratory Data Analysis
- Sentiment Distribution
- Review Length Analysis
- Word Cloud Visualization

### 5. Feature Engineering
- TF-IDF Vectorization
- 5000 Features Generated

### 6. Model Building
- Logistic Regression

### 7. Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Results

| Metric | Value |
|----------|----------|
| Accuracy | 86.7% |
| Positive Reviews | 78.1% |
| Negative Reviews | 14.4% |
| Neutral Reviews | 7.5% |

---

## Key Insights

- Most reviews are positive.
- Positive sentiment dominates the dataset.
- Neutral reviews are comparatively harder to classify.
- Logistic Regression performs effectively for sentiment prediction.

---

## Visualizations

- Sentiment Distribution Bar Chart
- Review Length Distribution
- Word Cloud
- Sentiment Percentage Pie Chart
- Confusion Matrix

---

## Project Structure

```text
amazon-review-sentiment-analysis
│
├── data
├── images
├── notebooks
│   └── sentiment_analysis.ipynb
│
├── report
│   └── insights_summary.md
│
└── README.md
```

---

## Future Improvements

- Random Forest Classifier
- XGBoost
- Advanced NLP Models
- Deep Learning Approaches

---

## Author

Bhavikta Gedam
