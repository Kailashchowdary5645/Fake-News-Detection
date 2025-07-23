# Fake News Detection Using Machine Learning

This project classifies news articles as **Real** or **Fake** using TF-IDF vectorization and Logistic Regression.

## Features
- Text cleaning and preprocessing
- TF-IDF feature extraction
- Logistic Regression model
- Evaluation with accuracy, confusion matrix, and classification report
- Prediction function for new inputs

## Installation
```bash
pip install -r requirements.txt
```

## Usage
```bash
jupyter notebook fake_news_detection.ipynb
```

### Example Prediction
```python
print(predict_news("Breaking: Scientists discover a cure for cancer!"))
```
Output:
```
Real News
```
