# 🛡️ Optimizing Credit Card Fraud Detection: A Study of Ensemble Learning and Robust Preprocessing Techniques

## 📝 Overview

This project presents a Machine Learning-based framework for detecting fraudulent credit card transactions. Developed as a university research project, it is accompanied by a comprehensive survey and research paper investigating limitations and research gaps identified in previous fraud detection studies.

The proposed framework combines advanced preprocessing techniques, threshold optimization, and multiple state-of-the-art Machine Learning models to improve fraud detection performance on highly imbalanced datasets.

---

## 🎯 Research Objective

The primary objective of this research is to address major challenges and gaps found in previous fraud detection papers, including:

- Handling highly imbalanced transaction datasets
- Reducing False Positives and False Negatives
- Improving fraud classification reliability
- Preventing data leakage during preprocessing
- Comparing multiple Machine Learning and Ensemble approaches
- Optimizing classification thresholds instead of relying solely on default probabilities

---

## 🧠 Methodology & Techniques

### 1️⃣ Data Preprocessing

- Data Cleaning and Validation
- Outlier Handling using `RobustScaler`
- Leakage Prevention through proper train-test separation
- Threshold Optimization for better fraud classification
- Handling highly imbalanced datasets

### 2️⃣ Machine Learning Models

The following models were implemented and evaluated:

-  Random Forest
-  XGBoost
-  LightGBM
-  Ensemble Learning Model

### 3️⃣ Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- PR-AUC

---

# 📊 Results Summary

| Model | Threshold | ROC-AUC | PR-AUC | Precision | Recall | F1-Score |
|---|---|---|---|---|---|---|
| Random Forest | 0.5611 | 0.9894 | 0.8225 | 0.91 | 0.64 | 0.75 |
| XGBoost | 0.9469 | 0.9961 | 0.8274 | 0.78 | 0.75 | 0.77 |
| LightGBM | 0.9596 | **0.9969** | **0.8536** | 0.84 | 0.76 | 0.80 |
| Ensemble Model | 0.8228 | 0.9965 | 0.8533 | **0.93** | **0.82** | **0.87** |

---

##  Best Ensemble Performance

```text
Best Threshold : 0.8227627745630562
Precision      : 0.9293764087152517
Recall         : 0.8241172551632245
F1-Score       : 0.873587570571649
ROC-AUC        : 0.9964855802922621
PR-AUC         : 0.8532832595212703
```

###  Key Findings

- **LightGBM** achieved the highest overall ROC-AUC and PR-AUC performance.
- The **Ensemble Model** achieved the best Precision and F1-Score after threshold optimization.
- Threshold tuning significantly improved fraud detection reliability on imbalanced datasets.
- Robust preprocessing techniques reduced the impact of outliers and enhanced model stability.

---

##  Research Contribution

This work contributes to the field of financial fraud detection by:

- Addressing limitations identified in previous studies
- Improving fraud detection robustness
- Applying optimized threshold-based classification
- Demonstrating strong performance on highly imbalanced data
- Providing a practical framework suitable for real-world financial systems

---

##  Technologies Used

- Python
- Scikit-learn
- XGBoost
- LightGBM
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---


##  Affiliation

**Computer Science Department**  
Faculty of Science  
Alexandria University, Egypt

---

## 👩‍💻 Team Members

- Rwan Hossam Eldein Mohammed
- Maha Salah Hussein
- Nada El Sayed Ali Hassan
- Nermeen Tarek Bakhit Mahmoud
- Arwa Khamis Galal

---

##  Research Links

- 📄 Research Paper: *Coming Soon*
- 📊 Survey Results: *Coming Soon*

---

## 📜 License

This project was developed for academic and research purposes.  
All rights reserved to the authors and Alexandria University.
