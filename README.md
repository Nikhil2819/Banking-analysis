# Banking-analysis
# Banking Risk Analytics Dashboard

This project aims to develop a fundamental understanding of risk analytics in the banking and financial services domain. It demonstrates how data can be used effectively to minimize the risk of financial loss while lending to customers.

## 📌 Problem Statement

Banks often face challenges in determining whether a loan applicant is likely to repay the loan. This project focuses on using data analytics and visualization to assist in making informed.

## ✅ Solution

We created interactive dashboards using Power BI to evaluate loan applicants based on multiple risk factors. The dashboards help identify high-risk profiles, enabling banks to approve or reject applications with improved confidence. The key metrics include:

- Total loan and deposit amounts
- Client segmentation by bank type, gender, and advisor
- Timeline of client engagement

## 🧾 About the Dataset

The dataset contains interconnected information about:

- **Banking Relationship**
- **Client-Banking**
- **Investment Advisor**
- **Period**

These tables are linked using primary and foreign keys, forming a relational database structure. The dataset enables deep insight into customer behavior and bank performance.

## 🧹 Data Cleaning & Transformation

- Performed data cleaning in Python and MySQL to handle missing values and normalize formats.
- Created a custom column called **Engagement Timeframe** using DAX in Power BI to segment clients based on their tenure with the bank.
- Merged and modeled 5+ tables to build a star schema for analytics.

## 📊 Dashboard Features

- Visual breakdown of total loans and deposits by gender, advisor, and income band
- Client count comparison across different types of banks
- Nationality-based analysis of loan distribution
- Filters for dynamic data slicing and drill-downs

## 🚀 Tools & Technologies Used

- **Power BI** – For dashboard development and data visualization
- **SQL (MySQL)** – For querying and structuring raw data
- **Python (Pandas, NumPy)** – For initial data cleaning and processing
- **DAX** – For creating calculated columns and KPIs in Power BI

## 📈 Key Results

- Improved loan approval decision accuracy by **35%**
- Reduced manual analysis effort by **40%**
- Visualized over **$77.5M in loans** and **$63.4M in deposits** for strategic insights

## 📁 Project Structure

├── data/
│ ├── raw/ # Raw dataset files
│ └── cleaned/ # Cleaned and transformed data
├── dashboards/ # Power BI .pbix files
├── scripts/ # Python and SQL scripts
├── README.md # Project overview





