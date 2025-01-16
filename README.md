# Sentiment Analysis on Kindle_Reviews.
This project compares the performance of RoBERTa (a transformer-based deep learning model) and VADER (a lexicon-based sentiment analysis tool) in analyzing sentiment from text data.

# Features
1. VADER: Lexicon-based sentiment analysis (faster, rule-based)
2.  RoBERTa: Deep learning-based sentiment analysis.
3. Performance comparison on different text inputs.

# Installation.

  1. Install Dependencies.
pip install torch transformers nltk

   2. Download NLTK resources (for VADER).
 import nltk
nltk.download('vader_lexicon')

# Comparison Insights
VADER: Uses predefined sentiment scores, making it faster but sometimes less accurate for complex language.
RoBERTa: Uses deep learning, providing context-aware sentiment classification (Positive, Neutral, Negative).

# Contributing
Feel free to fork and improve this project by adding more evaluation metrics or datasets!

# License
MIT License


   
