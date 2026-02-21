# 🏥 Healthcare Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on hospital admission data to identify patterns in patient admissions, medical conditions, billing amounts, and length of hospital stay.

The objective is to derive meaningful business insights that can support hospital management in operational and financial decision-making.

---

## 🎯 Objectives

- Analyze distribution of medical conditions
- Examine admission type patterns
- Study hospital billing trends
- Calculate and analyze length of stay
- Identify relationships between stay duration and billing amount
- Generate business-focused insights

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 📊 Dataset Information

The dataset contains hospital patient records with the following fields:

- Patient Name  
- Gender  
- Medical Condition  
- Admission Type  
- Date of Admission  
- Discharge Date  
- Billing Amount  

📌 *Dataset Source:*  
The dataset used in this project is publicly available on Kaggle.  
(Dataset file is not included in this repository.)

---

## 🧹 Data Cleaning & Preprocessing

- Removed rows with missing critical values
- Converted admission and discharge dates to datetime format
- Standardized patient name formatting
- Created a new feature: **Length_of_Stay**
- Performed outlier detection on billing amount

---

## 🧠 Feature Engineering

### Length_of_Stay

Length_of_Stay = Discharge Date − Date of Admission

This feature enables analysis of:

- Hospital occupancy patterns
- Revenue impact of extended stays
- Relationship between stay duration and billing amount

---

## 📈 Key Analysis Performed

### 1️⃣ Medical Condition Distribution
Identified the most frequent medical conditions among patients.

### 2️⃣ Revenue by Medical Condition
Analyzed which conditions generate the highest total billing revenue.

### 3️⃣ Admission Type Analysis
Compared emergency and planned admissions in terms of frequency and average billing amount.

### 4️⃣ Length of Stay Distribution
Studied how long patients typically stay in the hospital.

### 5️⃣ Correlation Analysis
Examined relationships between numeric variables, especially:
- Length_of_Stay
- Billing Amount

---

## 💡 Key Business Insights

- Certain medical conditions contribute disproportionately to overall hospital revenue.
- Emergency admissions tend to have higher average billing amounts.
- Longer hospital stays are positively correlated with increased billing.
- While most patients have short stays, extended stays significantly impact total revenue.

These insights can help hospital management optimize resource allocation, cost planning, and operational efficiency.
