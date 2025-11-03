
# 📊 Sales Performance Dashboard – Power BI Project

## 💼 Project Overview
This project showcases my ability to transform raw sales data into meaningful business insights using **Power BI**.  
I built an interactive **Sales Performance Overview Dashboard** that highlights key metrics such as **total revenue**, **units sold**, and **average profit margin**, with insights across **regions**, **product categories**, and **months**.

The goal was to create a tool that enables business leaders to quickly assess sales performance, identify top-performing areas, and make data-driven decisions.

---

## 🧹 Data Cleaning & Preparation
After loading the dataset into Power BI, I performed several cleaning and transformation steps to ensure accuracy and consistency:

- ✅ Removed **duplicates** to maintain data integrity  
- ✅ Changed **data types** for accurate calculations and visuals  
- ✅ Renamed **columns** for clarity and standardization  

These steps laid a strong foundation for reliable analysis and reporting.

---

## 🧮 DAX Measures Created
To support insightful analysis, I created two custom **DAX measures**:

1. **Total Revenue**
   ```DAX
   Total Revenue = SUM(ORDERS[SALES])
   ```

2. **Average Profit Margin**
```DAX
    Average Profit Margin =
DIVIDE(
    SUM('Orders'[Profit]),
    SUM('Orders'[Sales]),
    0
)
```
These measures allowed for real-time, dynamic calculations across filters such as region, month, and product category.

## 📈 Dashboard Highlights

The dashboard provides a clear snapshot of business performance with key insights:

💰 Total Revenue: $2M

📦 Units Sold: 25K

📊 Average Profit Margin: 11.6%

Key Insights:

* Technology leads all product categories with $0.7M in sales.

* Sales are evenly distributed across all regions — indicating potential for targeted growth.

* Monthly sales trend shows consistent growth, peaking in April.

* The average profit margin of 11.6% demonstrates stable profitability.

## 🧭 Dashboard Features

* KPI Cards: Revenue, Units Sold, Profit Margin

* Bar Charts: Sales by Region, Sales by Product Category

* Line Chart: Monthly Sales Trend

* Slicers: Month, Region, and Product Category filters for interactivity

Insight Section: Summary of key business observations

## 🧰 Tools & Technologies Used

Power BI Desktop – for visualization and dashboard creation

DAX (Data Analysis Expressions) – for dynamic calculations

Data Transformation Tools – for cleaning and preparation

## 🖼️ Dashboard Preview
<img width="1842" height="930" alt="Image" src="https://github.com/user-attachments/assets/cd70fa40-2709-413f-8698-7b5ec31f9887" />

## Screen Recording


## 🚀 Outcome

* This project demonstrates my ability to:

* Clean and transform real-world datasets

* Create meaningful visualizations and KPIs

* Derive actionable insights from data

* Communicate findings effectively through design and storytelling

The result is a professional and interactive dashboard that supports informed business decisions and highlights my growing expertise in data analytics and Power BI.

## 👨🏾‍💻 About Me

 Kofi Obeng Nti
📍 Based in the United Kingdom

Aspiring Data Analyst and Accounting Professional passionate about turning data into insights that drive growth and efficiency.
Always learning, always improving. ☀️

🔗 Connect with me on LinkedIn : https://www.linkedin.com/in/kofi-obeng-nti-aa3884140/
 to see more of my data analytics and Power BI projects
Email : kofiobengnti@gmail.com

