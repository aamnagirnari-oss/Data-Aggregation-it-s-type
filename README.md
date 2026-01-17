# Data-Aggregation-it-s-type
This practical demonstrates data aggregation in data mining using Python and Pandas. It covers basic aggregation types (sum, mean, count, min, max), multi-level grouping, time aggregation (monthly, quarterly, yearly sales), and spatial aggregation by region and city using a real-world–style dataset.


---

```markdown
# Practical: Data Aggregation in Data Mining

## 📌 Overview
This project demonstrates **Data Aggregation techniques in Data Mining** using **Python and Pandas**. It includes basic aggregation methods, multi-level aggregation, **time-based aggregation**, and **spatial aggregation** using a sample sales dataset.

---

## 🎯 Objective
To understand and implement:
- Data aggregation concepts in data mining
- Basic aggregation functions (sum, mean, count, min, max)
- Multi-level aggregation
- Time aggregation (monthly, quarterly, yearly)
- Spatial aggregation (region-wise and city-wise)

---

## 🛠 Tools & Technologies
- Python 3.x  
- Pandas  
- Jupyter Notebook / Google Colab  

---

## 📂 Dataset Description
The dataset contains sales information with the following attributes:

| Column | Description |
|------|------------|
| Region | Sales region (North, South, East, West) |
| City | City within the region |
| Product | Product type (A, B, C) |
| Sales | Sales amount |
| Quantity | Units sold |
| Date | Transaction date |

---

## 🔹 Aggregation Types Implemented

### 1. Basic Aggregation
- Sum aggregation (total sales)
- Mean aggregation (average sales & quantity)
- Count aggregation (number of records)
- Custom aggregation (minimum & maximum sales)

### 2. Multi-Level Aggregation
- Aggregation by **Region and Product**

---

## ⏱ Time Aggregation
Time aggregation is performed using the `resample()` function after setting the Date column as index.

Implemented:
- Monthly sales aggregation
- Quarterly sales aggregation
- Yearly sales aggregation

---

## 🌍 Spatial Aggregation
Spatial aggregation groups data based on geographical attributes.

Implemented:
- Sales by region
- Sales by city
- Sales by region and city

---

## 📊 Sample Outputs
- Total sales by region
- Mean sales by product
- Monthly, quarterly, and yearly sales summaries
- Region-wise and city-wise sales distribution

---

## 📁 Project Structure
```

Data-Aggregation-Practical/
│── aggregation_practical.ipynb
│── README.md

```

---

## ✅ Conclusion
This practical provides hands-on experience with aggregation techniques used in data mining. It shows how Pandas can efficiently summarize and analyze data using both **time** and **spatial** dimensions.

---

## 👩‍💻 Author
**Girnari Aamna**

---
