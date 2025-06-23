# The Influence of Twitter Sentiment on Bitcoin Price Movements

This project explores the relationship between public sentiment on Twitter and Bitcoin price movements from 2015 to 2025. By analyzing over 4.8 million tweets and applying various Natural Language Processing (NLP) and machine learning techniques, the study aims to uncover patterns that indicate whether Twitter sentiment serves as a leading or lagging indicator of market behavior.

## Installation Guide

1. **Clone the repository:**
```bash
git clone https://github.com/yapwh1234/SMC-Project
```

2. **Download the dataset manually** (due to size restrictions):
- Go to [this Kaggle notebook](https://www.kaggle.com/code/erdeq1024/bitcoin-price-analysis-by-tweets?select=Bitcoin_tweets.csv)
- Download the file `Bitcoin_tweets.csv` and place it in the `./data` folder.

4. **Run the Jupyter notebooks:**
```bash
jupyter notebook
```

---
## Data Visualization

### 1. Sentiment Distribution Comparison
![Sentiment Comparison](https://github.com/user-attachments/assets/d366f870-f8ae-4b54-bd99-78aba5af31b4)

### 2. TextBlob Sentiment Strength Distribution
![TextBlob Strength](https://github.com/user-attachments/assets/03fdce83-aa3f-4139-8e3a-15924fb806a8)

### 3. VADER Sentiment Strength Distribution
![VADER Strength](https://github.com/user-attachments/assets/add91c01-db19-45bf-82c0-3e49862cbfe0)

### 4. AFINN Sentiment Strength Distribution
![AFINN Strength](https://github.com/user-attachments/assets/90e15a6f-635e-441b-9349-3236f927a4e5)

### 5. Model Performance Comparison (Accuracy, Precision, Recall, F1)
![Model Performance](https://github.com/user-attachments/assets/64f9230e-b41d-496b-aef2-ee95f1e8ed06)


## Tools & Technologies

- Python (Pandas, NLTK, spaCy, Sklearn, Transformers, PyTorch)  
- Pretrained Models: `bert-base-uncased`, `deberta-v3-base-absa-v1.1`  
- Sentiment Tools: VADER, TextBlob, Afinn  
- Jupyter Notebook  
- Matplotlib, Seaborn  

## Key Features

- **Tweet Preprocessing**: Tokenization, lemmatization, stopword removal  
- **Feature Engineering**: TF-IDF, Word2Vec, contextual embeddings  
- **Sentiment Analysis**: Lexicon-based + fine-tuned transformer models  
- **Model Comparison**: Logistic Regression, SVM, BiLSTM, Hier-GCNN, BERT (DeBERTa)  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, Confusion Matrix  

## Future Work

Moving forward, this project can be extended in several directions:

1. **Temporal Causality Analysis**: Applying Granger causality tests to assess whether sentiment movements predict Bitcoin price fluctuations.  
2. **Emotion Classification**: Enhancing sentiment classification beyond positive/negative to include fear, greed, hype, and uncertainty.  
3. **Domain-Specific Fine-Tuning**: Further refining transformer models using financial-specific corpora to improve domain relevance.  
4. **Real-Time Monitoring**: Deploying a live dashboard for real-time Bitcoin sentiment tracking with price overlay.  

## Contributors

- **Choo Chee Choong** (1221302637) – MMU  
- **Yap Weng Hong** (1211103023) – MMU  


