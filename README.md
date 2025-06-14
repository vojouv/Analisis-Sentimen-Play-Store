# ☕ Sentiment Analysis of Kopi Kenangan App Reviews Using Machine Learning

The rapid growth of coffee shop businesses has led coffee entrepreneurs to explore various strategies to attract and retain their market. This project aims to perform a **sentiment analysis** on user reviews of the **Kopi Kenangan** mobile application using three machine learning models: **Support Vector Machine (SVM)**, **Decision Tree (DT)**, and **Random Forest (RF)**.

---

## 🧠 Objective

To compare and evaluate the performance of multiple machine learning models in predicting public sentiment toward the Kopi Kenangan app, and determine which model yields the most accurate results.

---

## 🔍 Methodology

- **Sentiment labeling** was conducted using two approaches: **score-based** and **lexicon-based** methods.
- The dataset contained class imbalance, which was addressed using the **SMOTE** (Synthetic Minority Over-sampling Technique) method.
- Three classification algorithms were used:  
  - Support Vector Machine (SVM)  
  - Decision Tree (DT)  
  - Random Forest (RF)
- Each model was trained and evaluated using both labeling approaches.

---

## 📊 Results

- The **SVM model with lexicon-based labeling** achieved the best performance.
- **Accuracy:** 94%  
- This model proved to be the most reliable for predicting sentiment polarity (positive, negative, neutral) in the context of Kopi Kenangan app reviews.

---
