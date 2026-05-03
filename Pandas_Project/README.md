# 📊 Customer Sales Analysis

## 🚀 Project Overview

This project focuses on cleaning, transforming, and analyzing a real-world **e-commerce transaction dataset** using Python and Pandas.

The dataset contains multiple real-world data issues such as missing values, inconsistent formatting, duplicates, and invalid entries. The goal is to make the data clean, reliable, and extract meaningful insights.

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Dataset Description

The dataset includes transaction-level data with the following columns:

* Transaction ID
* Customer ID & Name
* Email
* Purchase Date
* Product Category & Product Name
* Quantity & Unit Price
* Total Amount
* Payment Method
* Shipping Country
* Customer Age
* Discount Percent

---

## ⚠️ Data Issues Identified

* Missing values in important columns
* Inconsistent data types
* Duplicate records
* Mixed formatting in customer names
* Invalid values (negative amounts, incorrect totals)
* Multiple emails for same customer
* Outliers in discount and pricing

---

## 🧹 Data Cleaning Steps

* Handled missing values using logical replacements
* Standardized text (Title case for names, lowercase emails)
* Converted data types to correct formats
* Removed duplicate records
* Fixed invalid and inconsistent values
* Verified calculations like total amount

---

## ⚙️ Feature Engineering

New features created:

* `net_amount` → after applying discount
* `discount_amount` → actual discount value
* `year_month` → extracted from purchase date
* `purchase_quarter` → quarterly analysis
* `customer_segment` → High / Medium / Low value customers
* `is_repeat_customer` → repeat purchase indicator

---

## 📊 Data Analysis Performed

### 🔹 Customer Analysis

* Unique customers count
* Repeat vs new customers
* Top customers by spending

### 🔹 Product Analysis

* Sales by category
* Most sold products
* Revenue distribution

### 🔹 Payment Analysis

* Most used payment methods
* Average transaction value

### 🔹 Geographic Analysis

* Sales by country
* Top performing regions

### 🔹 Time Series Analysis

* Monthly sales trend
* Order patterns over time

---

## 📈 Visualizations

* Bar chart → Sales by category
* Pie chart → Payment method distribution
* Histogram → Customer age distribution
* Line chart → Sales trend
* Box plot → Order value comparison
* Scatter plot → Age vs spending

---

## 📁 Project Structure

```
Data_Analytics_Projects/
│
├── Pandas_Projects/
│   ├── pandas_project.ipynb
│   ├── student_sales_data.csv
│   
│
└── README.md
```

---

## 📤 Output

* ✅ Cleaned dataset (`cleaned_sales_data.csv`)
* ✅ Jupyter Notebook with full analysis
* ✅ Visual insights & business conclusions

---

## 🔍 Key Insights

* High-value customers generate majority of revenue
* Electronics category contributes highest sales
* Credit Card is the most used payment method
* Repeat customers tend to spend more
* Discounts influence purchase behavior significantly

---

## 💡 Learning Outcomes

* Real-world data cleaning techniques
* Data preprocessing using Pandas
* Feature engineering
* Data visualization
* Extracting business insights from raw data

---

## 📌 Conclusion

This project demonstrates how raw, messy data can be transformed into meaningful insights using data analytics techniques. It reflects practical skills required for a **Data Analyst role**.

---

## ⭐ Future Improvements

* Build dashboard using Power BI / Tableau
* Add machine learning for prediction
* Automate data cleaning pipeline

---

## 🙌 Connect With Me

If you like this project, feel free to connect and give a ⭐ to the repo!
