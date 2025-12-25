# SQL Projects

Learning SQL by solving real data problems.

This repository contains my SQL practice and mini-projects focused on working with real-world datasets. The goal is to move beyond learning syntax and build hands-on experience in data cleaning, transformation, and analysis.

---

## Project 01: Data Cleaning – Layoffs Dataset

### Objective
Clean a raw layoffs dataset to make it suitable for exploratory data analysis (EDA) and further insights.

---

### Key Tasks Performed

- Removed duplicate records using `ROW_NUMBER()` with `PARTITION BY`
- Standardized inconsistent values across text columns
- Handled NULL values based on context instead of dropping rows blindly
- Removed rows and columns with low analytical relevance

---

### Concepts & SQL Features Used

- Common Table Expressions (CTEs)
- Window Functions (`ROW_NUMBER`)
- Conditional filtering
- Data standardization techniques
- Basic data quality checks

---

### Tools

- MySQL

---

### Outcome

A clean and structured dataset that can be directly used for EDA and trend analysis.

---

### Future Work

- Exploratory Data Analysis (EDA)
- Writing analytical queries to uncover patterns
- Adding more datasets and SQL projects to this repository

---

This repository will be updated regularly as I continue learning and applying SQL to different datasets.
