# 🚀 YouTube Comment Sentiment & Toxicity Analyzer

An end-to-end **Machine Learning + NLP web application** that analyzes YouTube comments to classify **sentiment (Positive, Negative, Neutral)** and detect **toxic content in real-time**.

🔗 **Live Demo:** https://apex-yt-comment-sentiment-analyser-three.vercel.app/

🔗 **GitHub Repository:** https://github.com/Rohit-code-77/APEX-YT-COMMENT-SENTIMENT-ANALYSER.git

---

# 📌 Overview

With the massive growth of user-generated content on YouTube, manually analyzing comments is inefficient.

This project provides an automated solution using **Machine Learning + NLP** to:

- 📊 Understand audience sentiment
- ⚠️ Detect harmful/toxic comments
- 📈 Generate actionable insights through an analytics dashboard

---

# ✨ Features

✅ **Sentiment Classification** *(Positive / Negative / Neutral)*

✅ **Toxicity Detection** *(Toxic / Non-Toxic)*

✅ **Interactive Dashboard**

- Pie Charts *(Sentiment Distribution)*
- Bar Graphs *(Category Counts)*
- Word Clouds *(Frequent Terms)*

✅ **Fast Processing**

- Analyze **1000+ comments within seconds**

✅ **Responsive Web Application**

✅ **CSV Upload + Manual Input Support**

---

# 🧠 Machine Learning Pipeline

```txt
CSV Input
   ↓
Text Preprocessing
   ↓
TF-IDF Feature Extraction
   ↓
Logistic Regression Models
   ↓
Sentiment + Toxicity Prediction
   ↓
Analytics Dashboard
```

---

# 🛠️ Tech Stack

## 👨‍💻 Backend / Machine Learning

- Python
- Scikit-learn
- NLTK
- Pandas
- NumPy

## 🎨 Frontend

- React + JavaScript
- Tailwind CSS
- Recharts
- Framer Motion

## ☁️ Deployment

- Vercel

---

# ⚙️ Methodology

## 🔹 Data Preprocessing

- Lowercasing
- URL & HTML Removal
- Tokenization
- Stop-word Removal
- Stemming *(Porter Stemmer)*

## 🔹 Feature Engineering

- TF-IDF Vectorization
- N-grams *(1,2)*
- Maximum Features: **10,000**

## 🔹 Models Used

- **Logistic Regression** *(Sentiment Classification — Multi-Class)*
- **Logistic Regression** *(Toxicity Detection — Binary)*

---

# 📊 Results

## 🎯 Sentiment Classification

- **Accuracy:** 84.6%
- **F1 Score:** 0.82

## ⚠️ Toxicity Detection

- **Accuracy:** 94.3%

---

# 🏆 Model Comparison

| Model | Accuracy |
|--------|----------|
| Naive Bayes | 78.2% |
| Decision Tree | 73.5% |
| Random Forest | 82.1% |
| SVM | 83.9% |
| Logistic Regression | **84.6%** |

---

# 📂 Project Structure

```txt
├── src/                  # React Frontend
├── ml/                   # ML Models & Preprocessing
├── public/
├── .env.example
├── README.md
└── package.json
```

---

# 🚀 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Rohit-code-77/APEX-YT-COMMENT-SENTIMENT-ANALYSER.git
cd APEX-YT-COMMENT-SENTIMENT-ANALYSER
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env.local` file:

```env
GEMINI_API_KEY=your_api_key_here
```

### 4️⃣ Run Development Server

```bash
npm run dev
```

---

# ⚠️ Limitations

- Does not fully understand sarcasm or deep contextual meaning
- Currently supports **English comments only**
- Requires **CSV input**
- No live YouTube API integration yet

---

# 🔮 Future Improvements

- 🤖 Integrate **BERT / Transformer Models**
- 🔗 Add **YouTube API** for live comment fetching
- 🌍 Multilingual Language Support
- 📱 Mobile Application Version
- 📊 Advanced Analytics Dashboard

---

# 👨‍💻 Authors

- **Rohit Kadian**
- **Vardan Kadian**
- **Manish Kumar**

---

# 📌 Acknowledgements

- Kaggle Datasets *(YouTube Comments & Toxicity)*
- Scikit-learn Library
- NLTK Library
- React Community

---

# ⭐ Show Your Support

If you like this project, **give it a ⭐ on GitHub!**