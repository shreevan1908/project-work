# 📊 SMS Spam Detection - Data Analysis Project

This project performs *exploratory data analysis (EDA)* on the *SMS Spam Collection Dataset*, a set of labeled messages tagged as either spam or ham (not spam). It uses only *basic Python libraries* — no internet downloads or external dependencies like NLTK are required.

---

## 📁 Dataset

- *File Name*: sms spam collection.txt
- *Format*: Tab-separated text file
- *Columns*:
  - label: Indicates whether a message is spam or ham
  - message: The actual text content of the message

---

## ✅ Goals

- Understand the distribution and characteristics of spam vs ham messages
- Explore text length, word frequency, and word count
- Visualize patterns using Matplotlib and Seaborn
- Do it all *offline*, without requiring NLTK or downloads

---

## 🛠 Tools & Libraries Used

- pandas: Data handling and preprocessing
- matplotlib: Data visualization
- seaborn: Advanced plots and comparison
- collections.Counter: Word frequency counting
- string: Basic text cleaning (punctuation removal)

> ⚠ No external NLP libraries (like NLTK or spaCy) were used in this project.

---

## 📌 Key Features of the Analysis

### 🔍 Data Cleaning
- Removed missing/null messages
- Encoded labels (spam → 1, ham → 0)
- Added message length and word count columns

### 📊 Visualizations
- Countplot of spam vs ham messages
- Boxplot and violin plot of message lengths
- Histograms for message length and word count
- Bar charts for top 10 most common spam and ham words

### 🧹 Text Cleaning
- Converted all text to lowercase
- Removed punctuation
- Removed a basic set of common stopwords using Python (no NLTK)

---

## 📸 Sample Visuals

| 📌 Plot Type        | Description                              |
|---------------------|------------------------------------------|
| Countplot         | Shows spam vs ham distribution           |
| Boxplot           | Compares message lengths                 |
| Violinplot        | Combines boxplot and density view        |
| Histplot          | Distribution of message length and words |
| Barplot           | Top 10 frequent words in spam/ham        |

---

## 🚀 How to Run the Project

1. Place the file sms spam collection.txt in your project directory.
2. Run the Python script or notebook that contains the analysis code.
3. Make sure you have the following libraries installed:

```bash
pip install pandas matplotlib seaborn
