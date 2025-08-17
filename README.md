# 📊 E-commerce Sales Dashboard

This project is focused on **Exploratory Data Analysis (EDA)** of an **E-commerce Store’s sales data**.  
Currently, the analysis is done for **Amazon sales data**, while future modules will cover **international sales and other platforms**.  

The project helps in identifying **sales trends, missing values, returns, cancellations, and overall performance metrics**.  
It is built using **Python, Pandas, Matplotlib, and Seaborn**.

---

## 🚀 Features Implemented (Amazon Sales Module)
### 1️⃣ Data Cleaning & Preprocessing
- Removed unnecessary columns from Amazon raw CSV  
- Handled **null values** and converted them into meaningful categories (e.g., returns, not shipped, cancelled orders)  
- Created a **data cleaning function** that:
  - Drops redundant columns  
  - Fixes missing values  
  - Converts dates into monthly periods  
  - Returns a clean DataFrame ready for analysis  

### 2️⃣ Null Value Analysis
- Identified records with zero/invalid `Amount`  
- Analyzed reasons:
  - **Returned orders**  
  - **Not shipped orders**  
  - **Cancelled transactions**  
- Visualized null value distribution using bar graphs  

### 3️⃣ Monthly Sales Trend
- Aggregated total sales month-wise  
- Created a **line chart** with:
  - Value labels for each point  
  - Highlighted **highest** and **lowest** sales month  
  - Summary text below the chart  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Pandas** → Data manipulation  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Development environment  

---

## 📂 Project Structure
