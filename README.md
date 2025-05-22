# 🔐 Phishing URL Detection using Machine Learning

This project detects phishing websites based on features extracted from URLs using traditional machine learning techniques.

## 🚀 Features
- Extracts 30+ URL-based features.
- Trains Random Forest, Logistic Regression, and XGBoost classifiers.
- Visualizes model performance.
- Ready-to-use for browser extensions or APIs.

## 📁 Project Structure
- `phishing_model.py`: Main script for preprocessing, training, and evaluation.
- `app.py`: (Optional) Flask web interface to test URLs.
- `notebooks/`: Jupyter notebooks for EDA and experimentation.
- `data/`: Dataset from open sources like Kaggle.

## 🧪 How to Run
```bash
git clone https://github.com/yourusername/phishing-url-detector.git
cd phishing-url-detector
pip install -r requirements.txt
python phishing_model.py

