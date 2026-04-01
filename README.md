# 📊 Support Ticket Classification System

## 🚀 Project Overview
This project builds a machine learning system to automatically classify customer support tickets into categories and assign priority levels.

The system uses Natural Language Processing (NLP) techniques with TF-IDF vectorization and Logistic Regression for accurate text classification.

---

## 🎯 Objectives
- Classify customer support tickets into predefined categories
- Assign priority levels (High / Medium / Low)
- Improve efficiency in handling customer complaints

---

## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib, Seaborn

---

## 📁 Dataset
The dataset used is the **Consumer Complaint Dataset**, which contains real-world customer complaint narratives and categories.

🔗 Dataset Link:  
https://www.kaggle.com/datasets/namigabbasov/consumer-complaint-dataset

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Selected relevant columns (text and category)
- Removed missing values
- Balanced dataset for fair training

### 2. Feature Extraction
- Applied TF-IDF Vectorization to convert text into numerical form

### 3. Model Building
- Used Logistic Regression for multi-class classification

### 4. Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Results
- Achieved approximately **85% accuracy**
- Balanced precision, recall, and F1-score across categories
- Confusion matrix shows strong classification performance

---

## 🚨 Priority Assignment
A rule-based approach is used to assign priority levels:

- **High Priority** → fraud, unauthorized access, urgent issues
- **Medium Priority** → errors, delays, service issues
- **Low Priority** → general inquiries

---

## 📉 Priority Distribution
- Low Priority: Majority of tickets
- Medium Priority: Moderate number of cases
- High Priority: Critical issues (less frequent)

---

## 🧾 Conclusion
This project demonstrates the effective use of NLP and machine learning techniques for automating support ticket classification.

It highlights the importance of:
- Data preprocessing
- Feature engineering
- Model evaluation

The system can be extended for real-world customer support automation.

---


