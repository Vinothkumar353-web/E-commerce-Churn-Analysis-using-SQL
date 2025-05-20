# 📊 Customer Churn Analysis – SQL Capstone

## 🚀 Objective
Analyze e-commerce customer churn using SQL to clean data, fix inconsistencies, derive insights, and explore behavioral patterns behind churn.

## 🛠 Tools
- MySQL
- CSV Dataset

## 📌 Key Steps

### 1. Data Cleaning
- Handled missing values using mean/mode
- Removed outliers (e.g., `WarehouseToHome > 100`)
- Fixed inconsistencies (e.g., `'Phone' → 'Mobile Phone'`)

### 2. Transformation
- Renamed columns for clarity
- Created `Churn_Status` and `ComplaintReceived` flags

### 3. Analysis Highlights
- Churn rate comparison by complaint status, city tier, and payment mode
- High churn in customers preferring "Laptop & Accessory" in Tier-1 cities
- Most active users prefer "Credit Card" with high satisfaction
- Distance from warehouse impacts churn behavior
- Insightful aggregation on cashback, coupons, and device usage

### 4. Returns Analysis
- Joined `customer_returns` with churn data
- Identified refund patterns among churned customers with complaints

## 📁 Files
- `churn_analysis.sql` – Full SQL script
- `README.md` – Project summary

## 📌 Insights
Customers with low satisfaction scores showed a significantly higher churn rate

Tier-2 cities recorded the highest churn in electronics-related orders

UPI users registered the highest average number of devices

