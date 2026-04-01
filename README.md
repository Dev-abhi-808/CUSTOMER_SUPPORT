# 🎫 Customer Support Ticket Classification using Machine Learning

## 📌 Project Overview
In real-world companies, customer support teams handle hundreds or even thousands of tickets daily, including emails, complaints, issue reports, and service requests.

Manually sorting these tickets is time-consuming and inefficient. Important or urgent tickets may be delayed, which negatively impacts customer satisfaction and company productivity.

This project focuses on building a **Machine Learning based system** that automatically classifies and prioritizes customer support tickets based on their text content.

Instead of creating a chatbot, this project demonstrates a real-world **Natural Language Processing (NLP)** application used in SaaS companies, IT service platforms, and enterprise support systems.

---

## 🚨 Problem Statement
Customer support teams face several common problems:

- Tickets are not categorized properly
- Urgent issues are not prioritized
- Teams spend too much time sorting tickets manually
- Delayed responses reduce customer satisfaction

This project solves these issues using Machine Learning.

---

## 🎯 Objective
The goal of this project is to build an ML system that can:

- Read customer support ticket text
- Automatically classify tickets into categories such as:
  - Billing Issue
  - Technical Issue
  - Account Issue
  - General Query
- Assign a priority level:
  - High
  - Medium
  - Low

This helps organizations respond faster and improve support efficiency.

---

## ⚙️ How the System Works

### 1️⃣ Data Collection
The dataset contains customer support tickets written in natural language text format.

### 2️⃣ Text Preprocessing
Raw text data is cleaned using NLP techniques:
- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Tokenization
- Lemmatization

### 3️⃣ Feature Extraction
Text is converted into numerical form using:
- Bag of Words
- TF-IDF Vectorization

### 4️⃣ Model Training
Machine Learning algorithms are used to classify support tickets:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

### 5️⃣ Model Evaluation
Performance is evaluated using:
- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🛠️ Tools & Technologies

### Programming Language
- Python

### Development Environment
- Jupyter Notebook
- VS Code

### NLP Libraries
- NLTK
- spaCy

### Machine Learning Libraries
- Scikit-learn
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

---

## 📂 Project Structure

