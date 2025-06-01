
# 📊 Zomato Reviews - Sentiment Analysis

This project analyzes customer sentiment from Zomato reviews using a combination of classical NLP techniques and modern deep learning models. We compare results from TextBlob (lexicon-based) with a transformer-based BERT model.

## 🔗 Repository
[GitHub Project Link](https://github.com/Thilaga-1/sentiment-analysis)

---

## 📁 Project Structure

```
├── Zomato_Sentiment_Analysis.ipynb    # Main Jupyter notebook
├── zomato_reviews.csv                 # Raw review dataset
├── Zomato_Report.pdf                  # Final report of the project
├── requirements.txt                   # Python dependencies
├── /screenshots                       # Visual output files
│   ├── sub_vs_pol.png                 # Polarity vs Subjectivity plot
│   ├── confusion_matrix.png           # BERT vs TextBlob confusion matrix
│   ├── wordcloud.png                  # Positive word cloud
│   ├── download.png                   # Negative word cloud
```

---

## 🧠 Models Used

1. **TextBlob (Lexicon-Based)**
   - Outputs: Polarity (-1 to 1), Subjectivity (0 to 1)
   - Simple thresholding for sentiment labels.

2. **BERT (Transformer-Based)**
   - HuggingFace pretrained model.
   - More context-aware sentiment classification.

3. **Naive Bayes with TF-IDF**
   - Traditional ML baseline.
   - Trained on cleaned reviews.

---

## 🧹 Preprocessing Pipeline

- URL, HTML tag, and digit removal
- Lowercasing
- Stopword removal (NLTK)
- Tokenization & normalization
- Clean text stored as `clean_review`

---

## 📊 Visualizations

### 1. Polarity vs Subjectivity (TextBlob)
![Polarity vs Subjectivity](screenshots/sub_vs_pol.png)

### 2. Confusion Matrix: BERT vs TextBlob
![Confusion Matrix](screenshots/confusion_matrix.png)

### 3. Word Cloud: Positive Reviews
![Positive Word Cloud](screenshots/wordcloud.png)

### 4. Word Cloud: Negative Reviews
![Negative Word Cloud](screenshots/download.png)

---

## 📈 Results

| Metric            | Value    |
|-------------------|----------|
| BERT Accuracy     | ~82%     |
| Naive Bayes Accuracy | ~77% |
| BERT Precision    | 98.87%   |
| BERT Recall       | 83.72%   |
| BERT F1-Score     | 90.6%    |

---

## 📄 Report

For a complete overview of methods, results, and analysis, read the full [📘 Zomato_Report.pdf](Zomato_Report.pdf).

---

## 🧰 Installation

1. Clone the repo:
```bash
git clone https://github.com/Thilaga-1/sentiment-analysis.git
cd sentiment-analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook Zomato_Sentiment_Analysis.ipynb
```

---

## 🔮 Future Work

- Fine-tune BERT on restaurant-specific reviews.
- Multi-class sentiment (aspect-based: food, delivery, service).
- Build an interactive dashboard using Streamlit.

---

## 🤝 Contributions

Open to suggestions, improvements, or PRs!
