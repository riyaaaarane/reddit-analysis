# 🧠 Reddit Company Sentiment Analysis

This project analyzes Reddit posts about various companies to understand public sentiment, compare discussions, and identify key topics using **Natural Language Processing (NLP)** techniques.

---

## 🚀 Project Overview

The goal of this project is to extract Reddit posts related to specific companies and perform sentiment and text analysis to uncover insights such as:
- How people feel about each company (positive, negative, neutral)
- Common themes and frequently discussed topics
- Comparison of public perception across multiple companies

---

## 🧩 Features

- **Data Extraction:** Collected Reddit posts mentioning company names and related discussions.  
- **Text Preprocessing:** Used **spaCy** for tokenization, lemmatization, and normalization.  
- **Feature Engineering:** Applied **TF-IDF vectorization** to represent textual data numerically.  
- **Sentiment Analysis:** Classified sentiments using **BERT-based** and **VADER** models.  
- **Comparative Analysis:** Compared sentiment trends across companies to identify public perception differences.  

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python |
| NLP | spaCy, NLTK, Transformers |
| Sentiment Models | VADER, BERT (CardiffNLP RoBERTa) |
| Vectorization | TF-IDF (scikit-learn) |
| Data Handling | pandas, NumPy |
| Visualization | matplotlib, seaborn |

---

## 📊 Workflow

1. **Data Collection:** Extracted Reddit posts related to selected companies.  
2. **Text Cleaning & Normalization:** Removed noise, punctuation, and stopwords.  
3. **Lemmatization & Tokenization:** Processed text using spaCy’s NLP pipeline.  
4. **TF-IDF Vectorization:** Converted clean text into numerical features.  
5. **Sentiment Classification:** Used sentiment models to label each post.  
6. **Analysis & Visualization:** Compared sentiment trends and top keywords.  

---
## 📈 Results

- Classified Reddit posts into **Positive**, **Negative**, and **Neutral** categories.  
- Identified top keywords and themes for each company.  
- Compared sentiment ratios to reveal **public perception trends**.

---

## 🧩 Future Enhancements

- Add topic modeling using **LDA or BERTopic**  
- Deploy as an interactive **dashboard (Streamlit/Plotly Dash)**  
- Automate Reddit data extraction via **PRAW or Pushshift API**

---

## 🤝 Contributions

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## 🧾 License

This project is licensed under the **MIT License**.
