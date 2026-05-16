# Phishing Email Detection Model

## Overview
This project is a Machine Learning-based Phishing Email Detection System developed using Python and Scikit-learn. The model analyzes email text content and classifies emails as either:

- Phishing
- Safe

The project demonstrates the use of Natural Language Processing (NLP) and Machine Learning techniques for cybersecurity applications.

---

## Features
- Detects phishing and legitimate emails
- Uses Machine Learning for classification
- Extracts text features using TF-IDF Vectorization
- Displays model accuracy
- Generates a confusion matrix visualization
- Allows users to test custom email messages

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Concepts Used
- TF-IDF Vectorization
- Naive Bayes Classification
- Train-Test Split
- Confusion Matrix
- Accuracy Evaluation

---

## Dataset
The dataset contains sample phishing and legitimate email messages labeled as:

- phishing
- safe

Example phishing emails:
- "You won a free iPhone. Click here now!"
- "Verify your bank account immediately."

Example safe emails:
- "Meeting scheduled for tomorrow."
- "Project report attached."

---

## How to Run the Project

Open terminal and run:

```bash
python phishing_detector.py
```