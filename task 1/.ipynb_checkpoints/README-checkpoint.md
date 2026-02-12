# Superstore Sales Data Wrangling & Preparation

## 📌 Project Overview
This project focuses on data immersion, data quality assessment, and data wrangling of the Superstore Sales dataset as part of the ApexPlanet Data Analytics Internship (Task-1).

The objective of this task is to transform raw transactional data into a clean, structured, and analysis-ready dataset that can be used for Exploratory Data Analysis (EDA), business intelligence reporting, and dashboard development in subsequent tasks.

---

## 🎯 Objective
- Understand the dataset structure and business context
- Identify data quality issues
- Perform data cleaning and transformation
- Create new features for improved analysis
- Generate a final cleaned dataset ready for analysis

---

## 📊 Dataset Description
The dataset contains retail sales transactions including customer information, product details, shipping data, and sales values. It enables analysis of sales trends, customer behavior, and regional performance.

Key data areas include:
- Order and shipping details
- Customer segmentation
- Product categories
- Geographic information
- Sales performance

---

## 🛠️ Steps Performed

### 1️⃣ Data Familiarization
- Loaded dataset using Pandas
- Examined structure using `.head()`, `.info()`, and `.describe()`
- Created a data dictionary documenting each variable

### 2️⃣ Data Quality Assessment
- Checked for missing values
- Identified duplicate records
- Verified data types
- Inspected inconsistencies in date formats

### 3️⃣ Data Cleaning
- Converted `Order Date` and `Ship Date` to datetime format
- Removed duplicate records
- Handled missing values where necessary
- Standardized data formats

### 4️⃣ Feature Engineering
New features were created to enhance analytical capability:
- **Order Year** – Extracted from Order Date
- **Order Month** – Extracted from Order Date
- **Shipping Days** – Difference between Ship Date and Order Date

