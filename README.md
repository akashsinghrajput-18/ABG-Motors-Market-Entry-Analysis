# 🚗 ABG Motors — Market Entry Analysis for India
**Data Science Capstone Project | Internshala**

A complete data science project to determine whether ABG Motors, a Japanese automobile manufacturer, should enter the Indian market. Using machine learning on Japanese customer data, I predicted potential buyers in India and delivered a data-driven business recommendation.

---

## 🎯 Business Problem

ABG Motors wants to expand into India but needs confirmation that the market can generate a **minimum of 12,000 car sales**. My job as a Data Scientist was to analyse customer data from Japan and India, build a predictive model, and give a final recommendation.

---

## ✅ Final Answer

| | |
|---|---|
| **Predicted Indian Buyers** | 69,508 |
| **Minimum Target** | 12,000 |
| **Times Above Target** | 5.8x |
| **Recommendation** | ✅ ABG Motors SHOULD enter India |

---

## 📊 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 67.07% |
| ROC-AUC | 0.72 |
| Precision | 68.90% |
| Recall | 78.03% |
| F1-Score | 73.18% |

---

## 🔍 Key Business Insights from Model

| Feature | Impact | Strategy |
|---------|--------|----------|
| 🚙 Car Age | Strongest predictor — old car owners 2.35x more likely to buy | Target owners of 5+ year old cars |
| 💰 Annual Income | Higher income = 53% more likely to buy | Push premium models to top earners |
| 👶 Customer Age | Older customers 13% less likely per year | Focus campaigns on 25–40 age group |
| 👨 Gender | Males 11.9% more likely to buy | Slight male tilt in marketing |

---

## 🛠️ Tech Stack

`Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Seaborn` `Tableau` `Google Colab`

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `ABG_Motors_Market_Entry_Data_Science_Project.ipynb` | Complete Python notebook with EDA, model, and predictions |
| `ABG_MOTORS.twb` | Tableau dashboard with 5 market insight charts |
| `JPN_Data.xlsx` | Japanese customer dataset (40,000 records) |
| `IN_Data_Clean.csv` | Indian customer dataset (70,000 records) |

---

## 🗺️ Project Workflow

**Data Loading → EDA → Preprocessing → Model Building → Evaluation → India Prediction → Tableau Dashboard**

1. Loaded and explored both Japan (40K rows) and India (70K rows) datasets
2. Encoded gender, scaled features with StandardScaler, split 80/20 train-test
3. Built Logistic Regression model — chosen for binary target and interpretability
4. Evaluated with Accuracy, AUC, Precision, Recall, F1-Score
5. Applied Japan-trained model to India data → predicted 69,508 buyers
6. Built Tableau dashboard with 5 charts showing market trends

---

*Dataset Source: Internshala Data Science Capstone Project*

*Author: AKASH SINGH

<img width="1008" height="803" alt="Screenshot 2026-05-31 211047" src="https://github.com/user-attachments/assets/ab51a85c-ae1e-4fbf-b90c-b87464290fa0" />
