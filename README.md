 Customer Data Preprocessing & Feature Engineering Project

## 📌 Project Overview
This project demonstrates complete data preprocessing, transformation, feature engineering, and final dataset preparation using Python (Pandas & Scikit-Learn).

The objective is to clean raw customer transaction data and prepare it for machine learning or analysis.

---

## 📂 Dataset Used
- File Name: `Users_with_nulls_except_user_id.csv`
- Null values intentionally added (~3-4%) for EDA practice
- `user_id` column kept untouched

---

# 🔎 Steps Performed

## 1️⃣ Handling Missing Values

- Numerical columns → **SimpleImputer (Mean Strategy)**
- Categorical columns → **Most Frequent Imputation**
- Optional enhancement → **KNN Imputer**
- Ensured `user_id` column remained unchanged

---

## 2️⃣ Data Transformation

✔ Converted date column into:
- Day
- Month
- Year

✔ Encoding:
- Label Encoding → Binary columns
- One-Hot Encoding → Nominal columns
- Ordinal Encoding → Ordered categories

✔ Applied:
- Binning (Low, Medium, High spending groups)
- Log Transformation
- Square Root Transformation

---

## 3️⃣ Feature Engineering

Created new features:

- Average Monthly Spend per Customer
- Purchase Frequency
- Days Since Last Purchase
- Category-wise Total Expenditure

---

## 4️⃣ Final Dataset Preparation

✔ Merged cleaned and engineered data  
✔ Compared records (before vs after)  
✔ Compared missing values (before vs after)  
✔ Counted outliers using IQR method  
✔ Generated final summary report  

---

## 📊 Final Output

- Cleaned Dataset → `Final_Cleaned_Dataset.csv`
- No missing values
- Additional engineered features
- Ready for ML modeling

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

## 🎯 Learning Outcomes

- Data Cleaning
- Feature Engineering
- Encoding Techniques
- Binning & Transformations
- Pipeline & ColumnTransformer
- Dataset Finalization

---

## 👩‍💻 Author
Purvi Talaviya

---
