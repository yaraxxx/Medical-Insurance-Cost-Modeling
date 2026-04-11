# 📂 Data Folder – Medical Insurance Cost Prediction

This folder contains the dataset used for the **Medical Cost Prediction Analysis** project.

## 📊 Dataset Overview

The dataset is sourced from Kaggle:

- **Name:** Medical Insurance Cost Prediction
- **Source:** https://www.kaggle.com/datasets/hetmengar/medical-insurance-cost-prediction
- **Type:** Tabular data
- **Use Case:** Regression (predicting individual medical insurance charges)

The dataset represents demographic and lifestyle attributes of individuals along with their corresponding medical insurance costs.

---

## 🧾 Data Dictionary

| Column Name | Description |
|------------|------------|
| `age` | Age of the primary beneficiary |
| `sex` | Gender of the beneficiary (male/female) |
| `bmi` | Body Mass Index (BMI), indicating body fat based on height and weight |
| `children` | Number of dependents covered by insurance |
| `smoker` | Smoking status (yes/no) |
| `region` | Residential region in the US (northeast, southeast, southwest, northwest) |
| `charges` | Individual medical costs billed by health insurance (**target variable**) |

---

## 🎯 Target Variable

- **`charges`**
  - Continuous numerical variable
  - Represents the **medical insurance cost**
  - This is the variable used for regression modeling

---

## 🔍 Data Characteristics

- Mix of **numerical and categorical features**
- No time-series component (cross-sectional dataset)
- Suitable for:
  - Regression modeling
  - Feature importance analysis
  - Interaction effect exploration (e.g., smoking × BMI)

---

## ⚠️ Notes & Assumptions

- The dataset is relatively small and may not fully represent real-world healthcare systems
- No temporal dimension → cannot be used for time-based forecasting
- Potential bias may exist (e.g., region or demographic distribution)

---

## 🛠️ Usage in This Project

This dataset is used to:

- Perform **Exploratory Data Analysis (EDA)**
- Build **regression models** to predict medical costs
- Analyze **key drivers of insurance charges**
- Generate **business and behavioral insights**

---

## 📌 File Structure
data/
│── insurance.csv # Main dataset
│── README.md # This file

---

## 📎 License & Attribution

This dataset is publicly available on Kaggle.  
Please refer to the original source for licensing details and usage terms:

https://www.kaggle.com/datasets/hetmengar/medical-insurance-cost-prediction




