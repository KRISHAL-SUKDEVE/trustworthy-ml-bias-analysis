# Trustworthy ML: Bias & Reliability Analysis

## Overview
This project explores how reliable a machine learning model is when making predictions across different groups. I used the Adult Income dataset and trained a classification model to predict whether a person earns more than 50K per year.

The main goal was not just to build a model, but to check whether its predictions are fair and consistent across genders.

---

## What I Did
- Cleaned and preprocessed the dataset  
- Encoded categorical variables  
- Trained a Logistic Regression model  
- Evaluated performance using accuracy and confusion matrix  
- Compared results for male and female groups  

---

## Results
- Overall accuracy was around 80–85%  
- Male accuracy: ~0.78  
- Female accuracy: ~0.90  

At first, it looks like the model performs better for females. But after looking deeper, the results show something interesting.

---

## Key Observation
The recall for the positive class (income >50K) is much lower for females (~0.23) compared to males (~0.48).

This means the model is missing a large number of actual high-income females. So even though overall accuracy is higher, the model is not equally reliable for both groups.

---

## What I Learned
- Accuracy alone can be misleading  
- Different groups can have very different error patterns  
- It’s important to look at metrics like recall and confusion matrix  
- Evaluating fairness is an important part of building ML systems  

---

## Tools Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

---

## Conclusion
This project helped me understand that building a model is not enough. It’s equally important to analyze how it behaves for different groups and whether it can be trusted in real-world scenarios.

---

## Author
Krishal Sukdeve
