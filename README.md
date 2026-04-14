# 🇵🇰 Pak-Liar NLP: Fake News Detection System

A complete Natural Language Processing (NLP) pipeline to classify political statements as **Fake** or **True**, built using machine learning techniques and real-world textual data.

---

## 🚀 Overview

This project focuses on detecting misinformation in political statements using NLP and supervised machine learning.

It includes:
- Data cleaning & preprocessing
- Feature engineering (TF-IDF, n-grams, Word2Vec)
- Model training (multiple classifiers)
- Evaluation & comparison

---

## 📂 Dataset

- File: `pak-Liar.csv`
- Features:
  - `statement` → Main text
  - `label` → Target (0 = Fake, 1 = True)
  - Metadata: subject, speaker, party, venue, etc.

---

## 🧠 NLP Pipeline

### 🔹 Text Preprocessing
- Lowercasing
- Removing URLs, HTML, punctuation
- Tokenization
- Stopword removal
- Lemmatization / Stemming

### 🔹 Feature Engineering
- TF-IDF Vectorization
- Count Vectorization (n-grams)
- Word2Vec embeddings
- Text length & metadata features

---

## 🤖 Models Used

- Multinomial Naive Bayes
- Complement Naive Bayes
- Logistic Regression
- Support Vector Machine (LinearSVC)
- SGD Classifier
- Random Forest
- Gradient Boosting
- Voting Classifier (Ensemble)

---

## 📊 Evaluation Metrics

- Accuracy
- Cross-validation scores
- Class distribution analysis
- Visualization of results

---

## 📈 Visualizations

- Class distribution 📊
- Statement length comparison 📏
- Top political parties & subjects 🏛️

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/pak-liar-nlp.git
cd pak-liar-nlp
```

### 2. Create virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## 📥 NLTK Setup

Run once inside Python:

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
```

---

## ▶️ Usage

Run the notebook:

```bash
jupyter notebook pak_liar_nlp.ipynb
```

---

## 🧪 Project Structure

```
📦 pak-liar-nlp
 ┣ 📜 pak_liar_nlp.ipynb
 ┣ 📜 pak-Liar.csv
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

---

## ⚠️ Challenges Faced

- Noisy real-world text data
- Imbalanced classes
- Feature selection complexity
- Model overfitting risks

---

## 💡 Future Improvements

- Deep Learning models (LSTM, Transformers)
- Urdu language support 🇵🇰
- Real-time API deployment
- Web interface (Flask / React)

---

## 🏁 Final Verdict

This is a strong, industry-relevant NLP project.

- Good for resume ✅  
- Good for FYP ✅  
- Can be extended into research with Urdu + transformers 🚀  

---

## 👤 Author

**Abdullah Haroon**  
Computer Science Student | NLP & AI Enthusiast

---

## ⭐ If you like this project

Give it a star and build something bigger on top of it.
