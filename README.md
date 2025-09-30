# 📊 Sentiment Analysis of MyPertamina App Reviews  

## 📌 Project Overview  
This project focuses on **sentiment analysis of user reviews on the MyPertamina app**.  
The dataset was collected through **web scraping**, followed by preprocessing steps, and then classified using two machine learning algorithms: **K-Nearest Neighbor (KNN)** and **Naïve Bayes Classifier (NBC)**.  

Since the dataset was **imbalanced**, the **SMOTE (Synthetic Minority Oversampling Technique)** method was applied to balance the data distribution before training the models.  

---

## 🛠️ Workflow  
1. **Data Collection**  
   - Reviews scraped from Google Play Store (MyPertamina app).  

2. **Preprocessing**  
   - Case folding (converting text to lowercase)
   - Cleaning (removing special characters, numbers, punctuation, etc.)  
   - Normalization 
   - Tokenization  
   - Stopword removal  
   - Stemming   

3. **Handling Imbalanced Data**  
   - Applied **SMOTE** to oversample minority class.  

4. **Modeling**  
   - **K-Nearest Neighbor (KNN)**  
   - **Naïve Bayes Classifier (NBC)**  

5. **Evaluation**  
   - Accuracy, Precision, Recall, F1-Score, and Confusion Matrix  

---

## 📊 Data Visualization: https://lookerstudio.google.com/reporting/2810c0b8-576b-409a-a6b8-4ec7e0cc6757
