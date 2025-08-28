# 🎯 TCS Sales Analysis – Interactive Dashboard

## 📖 Description

This project demonstrates Sales Data Analysis for TCS using Python.
The notebook tcs.ipynb explores, cleans, and visualizes sales transactions, and builds an interactive dashboard to gain insights into customer behavior, product categories, and revenue trends.

The project highlights how businesses can leverage EDA (Exploratory Data Analysis) and visual analytics to make data-driven decisions.

## 📂 Dataset

File: tcs.csv (exported from company transaction system)

Size: ~few thousand rows

Features:

TransactionID

CustomerID

Gender

Age

City

ProductCategory

Quantity

Price

TotalAmount

PurchaseDate

PaymentMode

Time-based features (Year, Month, Day, AgeGroup) were derived for trend analysis.

## 🔹 Problem Statement & Tasks

📌 Analyzing TCS Sales Transactions
Objective: Understand who buys what, when, and how much.

Tasks:

Perform data cleaning & preprocessing

Analyze demographics (gender, age, city) vs spending

Identify top-selling product categories

Study payment modes distribution

Visualize sales trends over time (Year/Month/Day)

Build interactive Streamlit dashboard for exploration

## Visualization

1. Age Distribution of Customers
   
<img width="695" height="468" alt="image" src="https://github.com/user-attachments/assets/a426f5ed-57c8-4893-b654-224cc249d8c5" />

2. Top 10 Cities by Number of Customers

   <img width="850" height="600" alt="image" src="https://github.com/user-attachments/assets/b0feef04-23d2-411b-94b2-91880ca97a0f" />

3. Monthly Sales Trend

   <img width="846" height="582" alt="image" src="https://github.com/user-attachments/assets/5976bff3-ddee-4b7e-97a3-8ef4136cea11" />

4. Payment Mode Usage

   <img width="481" height="502" alt="image" src="https://github.com/user-attachments/assets/a1a95bd2-e2d2-4f56-8c31-963c9a17625b" />



## ⚙️ Methods

Data processing with Pandas & NumPy

Visualization using Plotly Express & Matplotlib

Interactive app built with Streamlit

Aggregated sales by customer, city, product, and time

KPI metrics (Revenue, Transactions, Avg. Basket Size)

## 📊 Results

✅ Sales trends show strong seasonality and city-level differences

✅ Product categories contributed unequally, with clear top performers 

✅ Gender & age analysis revealed spending behavior patterns

✅ Payment mode distribution highlighted customer preferences

✅ Interactive dashboard enables filtering by year, city, and product category

## 📦 Requirements

Install dependencies with:

pip install pandas numpy matplotlib plotly streamlit

## ▶️ How to Run

Open Jupyter Notebook:

jupyter notebook tcs.ipynb


Or run the interactive dashboard:

streamlit run app.py

## 📈 Key Insights

Customer demographics directly influence sales volumes

City & region analysis shows where sales are strongest

Product categories drive different margins and volumes

Payment mode preferences can inform future promotions

Dashboards make insights accessible for decision-makers

## 🚀 Future Work

🔹 Add predictive models for sales forecasting

🔹 Integrate with real-time sales data pipeline

🔹 Deploy dashboard to Streamlit Cloud / Heroku / AWS

🔹 Extend analysis with customer segmentation & clustering
