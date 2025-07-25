# 📰 News Article Summarizer + Sentiment Analyzer

This is a simple Streamlit app that summarizes news articles and performs sentiment analysis using NLP. Just paste a URL of a news article, and the app will:
- Extract the title, authors, and publish date  
- Summarize the article  
- Analyze its sentiment (Positive / Neutral / Negative)

---

## 🚀 Live Demo

> Not available yet. You can run it locally by following the instructions below 👇

---

## 🛠️ Features

- **Summary Generation** using `newspaper3k`
- **Sentiment Analysis** using `TextBlob`
- Simple and clean **Streamlit UI**
- Handles **403 errors** with random user-agent headers

---

## 📦 Requirements

- Python 3.7+
- `streamlit`
- `nltk`
- `newspaper3k`
- `textblob`

---

## ⚙️ Setup Instructions

### Option 1: Using `venv` 

```bash
# 1. Clone the repository
git clone https://github.com/preettrank53/News-Article-Summarizer-with-Sentiment-Analysis.git
cd news-summarizer

# 2. Create a virtual environment
python -m venv env

# 3. Activate the virtual environment
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the app
streamlit run app.py
```

### Option 2: Using Conda (Recommended)
```bash
# 1. Clone the repository
git clone https://github.com/preettrank53/News-Article-Summarizer-with-Sentiment-Analysis.git
cd news-summarizer

# 2. Create and activate conda environment
conda create -p venv python=3.10
conda activate venv/

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run app.py

