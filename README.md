# 📊 Sentiment Analysis of Zomato Reviews

This project performs sentiment analysis on restaurant reviews using three different approaches:
- **TextBlob**: Lexicon-based sentiment scoring
- **BERT**: Transformer-based deep learning model from Hugging Face
- **Naive Bayes**: Traditional machine learning using TF-IDF features

It includes text preprocessing, polarity classification, model evaluation, visualizations (confusion matrices, word clouds), and comparison of model performance.

---

## 📁 Project Structure

```
sentiment-analysis/
├── zomato_sentiment_analysis.py       # Main analysis script
├── zomato_reviews.csv                 # Dataset of restaurant reviews
├── requirements.txt                   # Python dependencies
├── README.md                          # Project documentation
├── .gitignore                         # Git ignore rules
└── LICENSE                            # MIT License
```

---

## ⚙️ Features

- Clean and preprocess raw review text
- Assign sentiment labels using TextBlob polarity
- Run BERT-based sentiment predictions
- Train & evaluate Naive Bayes classifier
- Compare accuracy of all approaches
- Display:
  - Confusion matrix of BERT vs TextBlob
  - Word clouds for positive and negative reviews
  - Polarity vs Subjectivity plot

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Thilaga-1/sentiment-analysis.git
cd sentiment-analysis
```

2. **Install the dependencies**

```bash
pip install -r requirements.txt
```

3. **Download NLTK stopwords**

```python
import nltk
nltk.download('stopwords')
```

---

## 🚀 How to Run the Script

Ensure the dataset file `zomato_reviews.csv` is in the same directory.

Then run the main script:

```bash
python zomato_sentiment_analysis.py
```

---

## 🧪 Technologies Used

- Python 3
- **NLP & ML**:
  - TextBlob
  - Transformers (BERT)
  - Scikit-learn
- **Visualization**:
  - Matplotlib
  - Seaborn
  - WordCloud
- **Text Processing**:
  - NLTK
  - Regex
  - TF-IDF

---

## 📈 Sample Outputs

- Confusion matrix: BERT vs TextBlob sentiment
- Accuracy score and classification report
- Word clouds by sentiment
- Polarity vs Subjectivity scatter plot

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and share for academic and non-commercial purposes.

---

## 🙋‍♀️ Author

**Thilaga**  
GitHub: [@Thilaga-1](https://github.com/Thilaga-1)
