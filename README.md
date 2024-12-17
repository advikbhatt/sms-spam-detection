# SMS Spam Detection

## Overview
This project implements a machine learning model to classify SMS messages as **spam** or **ham** (not spam). The goal is to create an efficient spam filter that can detect unwanted messages and improve user experience.

## Features
- Text preprocessing: Lowercasing, tokenization, stemming, and removal of stopwords and punctuation.
- Exploratory Data Analysis (EDA) to understand patterns in the dataset.
- Multiple classification algorithms tested, including Naive Bayes, SVM, and Ensemble models.
- Final deployment with a Naive Bayes model for predictions.

## Dataset
The dataset used is the [SMS Spam Collection Dataset]([https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)), consisting of labeled SMS messages categorized as **spam** or **ham**.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/sms-spam-detection.git
   cd sms-spam-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the dataset:
   - Place the dataset file (`spam.csv`) in the root directory.
2. Run the jupyter notebook file
3. Run app.py 
 ```bash
   streamlit run app.py
   ```

## Models Used
- Multinomial Naive Bayes

## Results
- **Accuracy (Naive Bayes):** 0.970986%
- **Precision (Naive Bayes):** 1.000000%


## Dependencies
- Python 3.x
- pandas
- numpy
- nltk
- scikit-learn
- matplotlib
- seaborn
- wordcloud
- xgboost

Install all dependencies using:
```bash
pip install -r requirements.txt
```

## Contributing
Contributions are welcome! If you'd like to contribute:
