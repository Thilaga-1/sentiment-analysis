# Sentiment Analysis of Zomato Reviews 🍽️

This project performs sentiment analysis on restaurant reviews using three methods:
- **TextBlob** (lexicon-based)
- **BERT** (pre-trained transformer model)
- **Naive Bayes** (traditional ML with TF-IDF)

It includes data preprocessing, model evaluation, confusion matrices, and word cloud visualizations.

---

## 📁 Files

- `Zomato_sentiment_analysis.py` – Main script with full analysis
- `zomato_reviews.csv` – Dataset used for sentiment analysis 
- `requirements.txt` – Python libraries used
- `README.md` – You're reading it

---

## 🔧 Installation

Clone the repo:

```bash
git clone https://github.com/yourusername/sentiment-analysis.git
cd sentiment-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run NLTK setup:

```python
import nltk
nltk.download('stopwords')
```

---

## ▶️ How to Run

Make sure `zomato_reviews.csv` is in the same directory.

Then run:

```bash
python Zomato_sentiment_analysis.py
```

---

## 📊 Features

- Cleans and tokenizes reviews
- Generates polarity labels using TextBlob
- Compares BERT and TextBlob predictions
- Trains and tests a Naive Bayes classifier
- Shows confusion matrix and word clouds

---

## 📈 Output Examples

- Accuracy comparison between BERT and TextBlob
- Word clouds for positive/negative reviews
- Scatter plot of polarity vs subjectivity

---

## 🧠 Technologies Used

- BERT via Hugging Face Transformers
- TextBlob
- Naive Bayes Classifier (Scikit-learn)
- Matplotlib & Seaborn for plotting
- WordCloud for visualization

---

## 📜 License

For academic and educational use.
