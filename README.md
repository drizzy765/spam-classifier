# Email Spam Classification Notebook

## Overview
This Jupyter Notebook (`spam_classification.ipynb`) implements an **email spam classification pipeline** using a pre-trained machine learning model. It processes email text, transforms it into feature vectors using a TF-IDF vectorizer, and predicts whether an email is **Spam** or **Ham** (non-spam).  

The notebook is designed for data scientists, ML enthusiasts, or anyone looking to classify emails programmatically.

### Key Features
- **Text Preprocessing**: Converts raw email text into numerical features using a pre-trained `TfidfVectorizer`.
- **Prediction**: Uses a pre-trained scikit-learn model to classify emails.
- **Reusability**: Includes a `predict_email` function for easy integration into other applications.
- **Dependencies**: Uses `joblib` for model loading and `scikit-learn` for feature extraction and prediction.

---

## Prerequisites
Ensure the following are installed on your system:

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Python libraries:
```bash
pip install notebook joblib scikit-learn
