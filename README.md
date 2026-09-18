Sure 👍 Academic Period-ஐ **2025–2029** என்று மாற்ற வேண்டும்.

# 📊 Task 11 – Basic Data Sorting & Filtering

## Superstore Dataset Exploration

A data exploration project completed as part of the **Veda Technology Data Analytics Internship – Task 11**.

This project demonstrates basic data exploration using sorting, filtering, multiple conditions, and business-question analysis on the **Superstore dataset**.

---

## 👨‍💻 Author

**R. Kaniga**

* 🎓 B.Tech – Artificial Intelligence & Data Science
* 🏫 Muthayammal Engineering College
* 📅 Academic Period: **2025–2029**

---

## 🎯 Task Objective

The objective of this task is to practice basic data exploration by:

* Sorting records based on sales
* Filtering records using single conditions
* Applying multiple filters simultaneously
* Preserving the original/raw dataset
* Answering simple business questions using the dataset
* Creating a structured Excel-compatible analysis workbook

---

## 🛠️ Tools & Technologies

* 🐍 Python
* 🐼 Pandas
* ☁️ Google Colab
* 📊 Excel / Excel-compatible workbook
* 📁 GitHub

---

## 📂 Dataset

**Dataset:** Sample Superstore

The dataset contains sales transaction information including:

* Order ID
* Order Date
* Ship Date
* Customer
* Segment
* Country
* City
* State
* Region
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit

### Dataset Information

| Metric         | Value |
| -------------- | ----: |
| Total Rows     | 9,994 |
| Total Columns  |    21 |
| Duplicate Rows |     0 |
| Missing Values |    11 |

The raw dataset was preserved without deleting or modifying the original records.

---

## 🔎 Data Exploration Performed

### 1. Sorting

The dataset was sorted by **Sales in descending order** to identify transactions with the highest sales values.

### 2. Technology Category Filter

Records belonging to the **Technology** category were filtered.

### 3. Technology + Corporate Filter

Multiple conditions were applied:

* Category = Technology
* Segment = Corporate

### 4. West + Furniture Filter

Multiple conditions were applied:

* Region = West
* Category = Furniture

### 5. High Sales + Positive Profit Filter

Records satisfying both conditions were identified:

* Sales >= 500
* Profit > 0

---

## 📈 Business Questions & Answers

### Question 1

**Which category generated the highest total sales?**

**Answer:** Technology

**Total Sales:** $836,154.03

### Question 2

**Which region generated the highest total profit?**

**Answer:** West

**Total Profit:** $108,418.45

### Question 3

**Which customer segment generated the highest sales?**

**Answer:** Consumer

**Total Sales:** $1,161,401.34

### Question 4

**Which sub-category generated the highest profit?**

**Answer:** Copiers

**Total Profit:** $55,617.82

### Question 5

**What are the total sales and profit for the Technology category?**

**Answer:** Technology

* **Total Sales:** $836,154.03
* **Total Profit:** $145,454.95

---

## 📁 Workbook Structure

The final workbook contains the following sheets:

```text
Veda_Task_11_Sorting_Filtering_Final.xlsx
│
├── Raw Data
├── Sorted by Sales
├── Technology Filter
├── Tech Corporate
├── West Furniture
├── High Sales Profit
└── 5 Answers
```
