# The Influence of Twitter Sentiment on Bitcoin Price Movements

This project explores the relationship between public sentiment on Twitter and Bitcoin price movements from 2015 to 2025. By analyzing over 4.8 million tweets and applying various Natural Language Processing (NLP) and machine learning techniques, the study aims to uncover patterns that indicate whether Twitter sentiment serves as a leading or lagging indicator of market behavior.


## Data Visualization

Visual screenshots such as sentiment trends over time, model comparison bar charts (Accuracy, F1-score), and a tweet-based word cloud have been added to the final report to visually support analysis findings. These visuals help illustrate how public sentiment has evolved and how each model performed.

(![Model Performance](https://github.com/user-attachments/assets/64f9230e-b41d-496b-aef2-ee95f1e8ed06)
)  
*Figure: Comparison across all model*


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


