# 🧠 HR Employee Attrition Prediction

## 📌 Overview
Predicting whether an employee will leave the company using Machine Learning,
based on HR data including satisfaction level, workload, salary, and promotions.

## 👥 Team Members — Taif University, CS Department
| # | Name |
|---|------|
| 1 | Saeed Nasser Saeed Mubarak |
| 2 | Ghaith Najem Al-Zahrani |
| 3 | Muath Majed Alarabi |
| 4 | Rayan Ruddah Altalhi |
| 5 | Faris Hamed Al-Harbi |
| 6 | Salem Mohammed Alattas |

## 🙋 My Contribution (Faris Al-Harbi)
- Built and trained the MLP Neural Network model
- Performed data preprocessing and feature engineering
- Compared performance across 4 ML models

## 🛠️ Technologies
- Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

## 📊 Models & Results
| Model | Accuracy | F1-Score | Recall |
|-------|----------|----------|--------|
| MLP (Neural Network) | 97.53% | 94.83% | 94.87% |
| Decision Tree | 97.58% | 94.97% | 95.90% |
| SVM | 95.67% | 90.72% | 88.90% |
| Naive Bayes | 79.91% | 62.86% | 71.36% |

## 🔍 Key Findings
- Low satisfaction is the strongest predictor of attrition (-0.39 correlation)
- Employees with too few (2) or too many (6-7) projects are more likely to leave
- Attrition risk increases after 4-5 years without career development
- Sales and technical departments had the highest attrition rates

## 📁 Dataset
HR Dataset with 14,999 employee records (satisfaction, workload, salary, promotions)
