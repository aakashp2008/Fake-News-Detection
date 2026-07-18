# Fake News Detection using Machine Learning

## Overview

This project detects whether a news article is **Fake** or **Real** using Machine Learning and Natural Language Processing (NLP) techniques. It uses text preprocessing, TF-IDF vectorization, and classification algorithms to build and evaluate a fake news detection model.

## Dataset

This project uses the **Fake News Detection Dataset** from Kaggle.

**Note:** The dataset is **not included** in this repository because the file size (32 MB) exceeds GitHub's normal web upload limit. Please download the dataset from Kaggle and place it in the project folder before running the notebook.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Models Used

- Logistic Regression
- Multinomial Naive Bayes

## Feature Extraction

- TF-IDF (Term Frequency–Inverse Document Frequency)

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Text Cleaning
4. Stopword Removal
5. TF-IDF Feature Extraction
6. Model Training
7. Model Evaluation
8. Performance Analysis

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Model Performance

**Accuracy:** 51.07%

### Confusion Matrix

| Actual \ Predicted | 0 | 1 |
|-------------------:|--:|--:|
| **0** | 1221 | 808 |
| **1** | 1149 | 822 |

## Project Structure

```text
Fake-News-Detection
├── Fake_News_Detection.ipynb
├── README.md
└── requirements.txt
```

## Installation

```bash
pip install -r requirements.txt
```

## How to Run

1. Download the Fake News Dataset from Kaggle.
2. Place the dataset in the project folder.
3. Open `Fake_News_Detection.ipynb` using Google Colab or Jupyter Notebook.
4. Run all cells in order.
5. View the evaluation metrics and confusion matrix.

## Results

The project classifies news articles into fake and real categories using Machine Learning and NLP techniques.

## Future Improvements

- Improve model accuracy using advanced NLP techniques.
- Train on a larger dataset.
- Implement deep learning models such as LSTM or BERT.
- Build a web application for real-time fake news detection.

## Author

**AAKASH P**

B.Tech Information Technology Student

Intern Alpha – Machine Learning Internship Project
