# Spam SMS Classification

## Project Overview

This project uses Machine Learning and Natural Language Processing (NLP) techniques to classify SMS messages as Spam or Ham (Not Spam).

The model was trained using TF-IDF vectorization and Support Vector Classification (SVC).

---

## Dataset

SMS messages labelled as:

- Ham (Legitimate Message)
- Spam (Unwanted Advertisement / Fraud)

---

## Technologies Used

- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Joblib

---

## Machine Learning Pipeline

1. Text Cleaning
2. TF-IDF Vectorization
3. Train/Test Split
4. LinearSVC Classification
5. Performance Evaluation

---

## Results

### Accuracy

**98.44%**

### Classification Report

| Metric | Ham | Spam |
|----------|----------|----------|
| Precision | 0.99 | 0.98 |
| Recall | 1.00 | 0.90 |
| F1 Score | 0.99 | 0.94 |

---

## Files Included

- Spam_sms.ipynb
- spam_model.pkl
- Confusion_Matrix.png

---

## Future Improvements

- Deep Learning (LSTM)
- BERT Transformer Model
- Web Application using Streamlit
- Real-time SMS Detection
