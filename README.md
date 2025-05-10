#  Fake News Detection System

A deployed machine learning application that detects whether a news article is real or fake based on its content. This project addresses the growing concern of misinformation spreading through digital media using Natural Language Processing (NLP).


 **[View Full Source Code](https://github.com/Puneet0123/fake-news-detection.com)**

---

##  Problem Statement

Fake news has become a serious issue in the digital age. The goal of this project is to build an intelligent system that can classify news articles as real or fake using machine learning and text processing techniques.

---

##  Features

- User-friendly Streamlit interface
- Input raw news content or paste full article
- Instant prediction: **Real** or **Fake**
- Displays model confidence score
- Word cloud of frequent fake/real terms (optional)
- Performance metrics visualization (accuracy, confusion matrix, etc.)

---

##  Tech Stack

- **Python 3.10+**
- **Natural Language Processing (NLP):** NLTK, Scikit-learn, TfidfVectorizer
- **ML Model:** Logistic Regression / Random Forest / Naive Bayes
- **Deployment:** Streamlit
- **Dashboard (Optional):** Plotly / Seaborn / Matplotlib

---

## Model Performance

- Accuracy: **X.XX**
- Precision: **X.XX**
- Recall: **X.XX**
- F1-Score: **X.XX**

---


##  Input & Output

- **Input:** News headline, paragraph, or article
- **Output:** `Real` or `Fake` with a confidence score

---

##  How to Run Locally

```bash
git clone https://github.com/yourusername/fake-news-detection-app.git
cd fake-news-detection-app
pip install -r requirements.txt
streamlit run app.py
