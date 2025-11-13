# 📧 Spam Email Classifier using Machine Learning

A Machine Learning project that classifies emails as **Spam** or **Not Spam** using text data.  
This project demonstrates the complete ML workflow — from data preprocessing to model deployment.

---

## 🧠 Project Overview
This project aims to automatically detect spam emails based on their content.  
Using **Natural Language Processing (NLP)** and a **Multinomial Naive Bayes** classifier, the model learns from past emails and predicts whether a new email is spam or not.

---

## ⚙️ Tech Stack
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **Algorithm:** Multinomial Naive Bayes  
- **Vectorization:** CountVectorizer  

---

## 🧩 Project Workflow
1. **Data Loading** – Loaded the `emails.csv` dataset using Pandas.  
2. **Data Cleaning** – Removed duplicates and handled missing values.  
3. **Data Preparation** – Split data into features (`text`) and labels (`spam`).  
4. **Text Vectorization** – Converted text into numerical form using `CountVectorizer`.  
5. **Model Training** – Trained a `MultinomialNB` model on the training data.  
6. **Model Evaluation** – Achieved **~99.6% accuracy** on the test dataset.  
7. **Prediction Demo** – Classified new sample emails as spam or not spam.  

---

## 📊 Model Performance
| Metric | Score |
|:-------:|:------:|
| Accuracy | 99.6% |
| Algorithm | Multinomial Naive Bayes |
| Feature Extraction | CountVectorizer |

---

## 🚀 How to Run the Project
```bash
# Clone this repository
git clone https://github.com/yourusername/spam-email-classifier.git

# Navigate to the project directory
cd spam-email-classifier

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook or Python file
jupyter notebook

