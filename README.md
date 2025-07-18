# Sentiment_Analysis
# Sentiment Analysis on Amazon Fine Food Reviews

This project performs **sentiment analysis** on a subset of the **Amazon Fine Food Reviews** dataset using **NLTK's VADER sentiment scoring**. It includes exploratory data analysis (EDA), natural language processing (NLP) techniques, and sentiment classification.

---

## 📦 Dataset

- **Source**: [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- **Downloaded via**: `kagglehub`
- **Subset used**: First 500 rows of the dataset (`Reviews.csv`)

---

## 🔍 Overview of Analysis

### 1. 📊 Exploratory Data Analysis (EDA)
- Visualized the distribution of review scores (1 to 5 stars).
- Checked data structure and previewed a sample of reviews.

### 2. 🧠 Natural Language Processing (NLP) with NLTK
- Tokenization, POS tagging, and Named Entity Recognition (NER).
- Explored sentence structure of sample reviews.

### 3. ❤️ Sentiment Analysis with VADER
- Used **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to assign polarity scores:
  - `pos`, `neu`, `neg`, and `compound`
- Applied sentiment scoring across all 500 reviews.

---

## 📚 Libraries Used

- `pandas`, `matplotlib`, `seaborn` — for data manipulation and visualization.
- `nltk` — for text processing and VADER sentiment analysis.
- `tqdm` — for progress tracking.
- `kagglehub` — to access the dataset programmatically.

---

## 📝 How to Run

1. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn nltk tqdm kagglehub
