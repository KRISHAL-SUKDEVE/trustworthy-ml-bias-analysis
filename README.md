# Trustworthy Machine Learning: Bias & Reliability Analysis

## 📌 Overview
This project explores the reliability and fairness of machine learning models by analyzing performance across demographic groups. Using the Adult Income dataset, a classification model is built to predict income levels and evaluate potential bias.

---

## 🎯 Objectives
- Build a machine learning classification model
- Evaluate model performance using standard metrics
- Analyze bias and reliability across gender groups
- Demonstrate limitations of accuracy as a fairness metric

---

## 📊 Dataset
- Adult Income Dataset (UCI)
- Contains demographic and income-related attributes
- Target variable: income (<=50K, >50K)

---

## ⚙️ Methodology
1. Data Cleaning and Preprocessing  
   - Handled missing values  
   - Converted data types  
   - Encoded categorical features  

2. Model Training  
   - Logistic Regression  
   - Feature scaling using StandardScaler  

3. Evaluation  
   - Accuracy  
   - Confusion Matrix  
   - Precision, Recall, F1-score  

4. Bias Analysis  
   - Performance comparison across gender groups  
   - Subgroup evaluation using classification metrics  

---

## 📈 Results

### Overall Performance
- Accuracy: ~80–85%

### Gender-wise Performance
- Male Accuracy: ~0.78  
- Female Accuracy: ~0.90  

### Key Insight
- Despite higher overall accuracy for females, the model shows **significantly lower recall for the positive class (income >50K) in females (~0.23)** compared to males (~0.48).
- This indicates that the model fails to correctly identify a large proportion of positive cases for females.

---

## ⚠️ Key Findings
- Accuracy alone is **not sufficient** to evaluate fairness  
- Model performance varies significantly across groups  
- Error distribution (false negatives) reveals deeper bias  
- Subgroup analysis is essential for trustworthy AI systems  

---

## 🧠 Conclusion
This project highlights the importance of evaluating machine learning models beyond overall accuracy. By analyzing subgroup performance, it becomes evident that models can behave differently across populations, raising concerns about fairness and reliability.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

---

## 🚀 Future Work
- Apply fairness-aware algorithms  
- Explore bias mitigation techniques  
- Extend analysis to other demographic attributes  

---

## 📎 Author
Krishal Sukdeve
