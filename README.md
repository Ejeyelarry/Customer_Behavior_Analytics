# Customer_Behavior_Analytics <br>
## 📊 Executive Summary  
This project explores *Online Retail Customer Behavior* using Excel for data cleaning and exploratory data analysis (EDA), and *Power BI* for visualization.  
The goal was to uncover key insights into how customers purchase, what products drive profits, and how these patterns can support better *marketing and sales strategies*.  

The dataset used captures sales transactions, product details, customer information, and profitability.  
Through EDA and visualization, I identified spending patterns, customer segmentation opportunities, and profitability trends that can drive strategic decision-making.  

---

## 💼 Business Problem  
Retail businesses often struggle to:  
- Understand *_customer purchasing behavior over time_*.  
- Identify *_high value and repeat customers_*.  
- Know which product categories or segments drive *_profitability_*.  
- Develop *_marketing strategies_* that target the right customers.  

This project aims to solve these by analyzing customer purchase frequency, spending distribution, profit margins, and product preferences using real-world retail data from Kaggle.  

---

## ⚙ Methodology  

### 1. Data Cleaning (Excel)
- Removed *duplicates*, blank rows, and irrelevant columns.  
- Standardized text using =PROPER(TRIM(CLEAN(A1)).  
- Fixed *date formats*.  

 ---
 ### 2. Exploratory Data Analytics ( Excwl Pivot Table )
 - Created Pivot Table to analyze :
 - 1.Product Category Vs Sales
 - 2.Product Subcategory vs Profit
 - 3.seasonal Trends
 - 4.Customer Type

 ### Findings From EDA
 - **Technology** accounted for the highest Sales and **58.24%** of the total Profits.
 - Office Supplies generated **34%** profit despite lower sales volume.
 - Furniture had strong sales but the lowest profit **(7.72%)**, suggesting discount or pricing issues.
 - 795 total customers, with purchase frequency ranging from **1–41** orders.

---

   ## POWER BI VISUALIZATION
   Data was loaded into Power Bi for interative dashboards divide into 3 pages
   
   ### Page 1 Sales Overview
   - KPIs :Total Sales, Total Profits, Total Orders, Average Order Value, Total Customer
   - Charts: Sales by Product Category, Sales by Product Subcategory,Monthly Sales Trend , Sales & Profit by Region
   - Slicer: Shipmode
     
     <img width="654" height="372" alt="Bussiness Summary" src="https://github.com/user-attachments/assets/07a80af0-713c-4486-9170-d1a3b2e4b25b" />

 ### Page 2 Customer Insight/Segmentation
 - KPIs: Total Customers, Customer Retention, AOQ per Customer, Preferred Shipmode, Profit Margin
- Charts: Customer type by Orderid, Shipmode by Orderid, Profit by Customer Segment, Top customer by Sales
- Slicer: Customer Segment
  
  <img width="668" height="376" alt="Customer behavior   Segmentation" src="https://github.com/user-attachments/assets/f814df25-be05-41ed-a975-91be70e911df" />

 ### Page 3 Product & Profit Analysis
 - KPIs: Most Profitable Category,Least Profitable Category,Best Selling Product, Loss Making Orders.
 - Charts: Total Profit by Quater,Profit Margin by Product category,Sales&Profits by Product category.
 - Slicers: Region
   
  <img width="667" height="376" alt="product and profit analysis" src="https://github.com/user-attachments/assets/1dfc65a2-85c2-4c72-aad7-2fabd9701250" />

  ---

 ## 🧠 Skills Applied
   - Excel: Data Cleaning, Pivot Tables, Data Validation, EDA.
   - Power BI: Data Modeling, DAX Measures, Dashboard Design.
   - Analytical Thinking: Insight extraction, segmentation, and storytelling
   - Business Intelligence: Translating raw data into actionable strategies

     ---
   
   ### INSIGHTS
   - The Technology category dominates profitability, signaling it should remain a top marketing focus.
   - Furniture underperforms in profit despite high sales — requiring pricing or supply chain optimization.
   - Repeat buyers drive consistent revenue, but retention can be improved through loyalty programs.

### Recomended Actions:
   

## 🗂 Repository Structure
Customer-Behavior-Analytics/
├── Data/
│   └── Cleaned_Online_Retail.xlsx
├── Reports/
│   └── Customer_Behavior_Dashboard.pbix
├── Images/
│   └── dashboard_preview.png
├── README.md
└── .gitignore



  -
     








   
 
  
  
  



   
 


