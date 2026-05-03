# 📊 Excel HR Analytics Project — TechVista Dataset

## 🚀 Project Overview

This project focuses on analyzing an **HR dataset of 50 employees** using Microsoft Excel.
The goal is to apply Excel functions to extract meaningful insights related to employee performance, salary, sales, and workforce distribution.

---

## 🛠️ Tools Used

* Microsoft Excel
* Excel Functions (Logical, Statistical, Conditional)

---

## 📂 Dataset Description

The dataset contains employee-level data with the following fields:

* Employee ID & Name
* Department & City
* Gender & Age
* Date of Joining
* Basic Salary
* Sales Amount & Sales Target
* Performance Rating
* Status (Active / Inactive)
* Experience (Years)
* Bonus Amount

---

## ⚠️ Data Issues Identified

* Invalid values (e.g., `#VALUE!` in city column)
* Inconsistent spellings (e.g., "Standard", "Stanadard")
* Mixed formatting in text columns
* Zero or missing bonus values
* Incorrect categorization in some fields

---

## 🧹 Data Cleaning Steps

* Fixed invalid entries (e.g., replaced `#VALUE!`)
* Standardized text formatting
* Corrected spelling mistakes
* Verified numeric columns (salary, bonus, sales)
* Ensured consistent categories

---

## 📊 Excel Functions Used

### 🔹 Basic Functions

* `AVERAGE()`
* `SUM()`
* `COUNT()`
* `COUNTA()`
* `COUNTBLANK()`

### 🔹 Logical Functions

* `IF()`
* Nested `IF()`

### 🔹 Conditional Functions

* `COUNTIF()`
* `SUMIF()`
* `AVERAGEIF()`
* `SUMIFS()`
* `AVERAGEIFS()`

---

## ⚙️ Feature Engineering (Using Excel)

Created new columns such as:

* Bonus Status → *Bonus Received / No Bonus*
* Target Achievement → *Achieved / Missed*
* Salary Band → *Senior / Junior*
* Employee Type → *Current / Ex-Employee*
* Age Category → *Gen Z / Millennial / Gen X*
* Performance Score (numeric mapping)
* Experience Level → *Fresher / Mid / Senior*
* Bonus Tier → *No Bonus / Standard / Premium*

---

## 📈 Key Analysis Performed

### 🔹 Employee Insights

* Total employees: **50**
* Active employees: **46**
* Gender distribution analysis
* Department-wise employee count

### 🔹 Salary Analysis

* Total salary payout
* Average salary
* Salary distribution by department

### 🔹 Sales Analysis

* Total sales generated
* Sales by city
* Target achievement comparison

### 🔹 Performance Analysis

* Performance rating distribution
* High-performing employees
* Relationship between performance & bonus

---

## 📊 Sample Insights

* Sales department has the highest number of employees
* Most employees fall under **Mid-Level experience**
* High performers often receive higher bonuses
* Active employees contribute the majority of sales
* Bonus distribution varies significantly across departments

---

## 📁 Project Structure

```
Excel_Assignment
│
├── Excel_Assignment 1.csv
└── README.md
```

---

## 📤 Output

* ✅ Completed Excel Assignment (50 Questions)
* ✅ Cleaned Dataset
* ✅ Derived Columns using formulas
* ✅ Analytical insights

---

## 💡 Learning Outcomes

* Strong understanding of Excel functions
* Data cleaning in Excel
* Logical & conditional analysis
* Business insight generation
* Real-world HR data handling

---

## 📌 Conclusion

This project demonstrates how Excel can be used as a powerful tool for **data analysis and business decision-making**, especially in HR and sales domains.

---

## ⭐ Future Improvements

* Create dashboards using Pivot Tables
* Build interactive reports
* Use Power BI for visualization
* Automate analysis using Python

---

## 🙌 Connect With Me

If you found this project useful, feel free to connect and give a ⭐ to the repository!
