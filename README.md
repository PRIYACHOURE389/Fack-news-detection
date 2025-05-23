# 📰 Fake News Detection Using Machine Learning

This project detects fake news articles using Natural Language Processing and machine learning algorithms.

## 🚀 Features
- Text preprocessing and cleaning
- TF-IDF vectorization
- Logistic Regression / Naive Bayes / Random Forest models
- Evaluation with accuracy, precision, recall, F1, AUC
- Easily extendable with deep learning or ensemble methods

## 🧰 Tech Stack
- Python, Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn

## 🗂️ Project Structure
- `src/`: source code modules
- `models/`: saved trained models
- `notebooks/`: Jupyter notebooks for EDA & experiments
- `data/`: dataset storage

## fake-news-detection structure/
│
├── data/
│   └── fake_news_dataset.csv       # Raw data
│
├── src/
│   ├── __init__.py
│   ├── config.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── evaluation.py
│
├── models/
│   └── model.pkl
│
├── notebooks/
│   └── EDA_and_Modeling.ipynb
│
├── .gitignore
├── README.md
├── requirements.txt
└── main.py

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
