 # 📊 Online Retail Sales Dashboard Report

## 📝 Introduction

This project showcases an interactive **Sales Dashboard** created using **Microsoft Excel**, based on a dataset of **500 online retail transactions**. The primary objective is to deliver **visual insights** using various **charts and slicers**, allowing users to interactively filter and analyze data across countries, categories, and payment methods.

---

## 📂 Dataset Description

The dataset consists of **500 rows** with the following fields:

- Order ID  
- Order Date  
- Customer Name  
- Country  
- Category  
- Product Name  
- Quantity  
- Unit Price  
- Total Sales  
- Payment Method  

It reflects real-world online sales across multiple countries and includes diverse product categories and payment methods.

---

## 📈 Dashboard Overview

The dashboard is built in Excel and comprises **six interactive charts** supported by slicers. These slicers enable dynamic filtering by:

- **Category**
- **Country**
- **Payment Method**

Each chart presents a different angle of the retail sales data, making the dashboard highly insightful for business decision-making.

---

## 📊 Chart Explanations

### 📍 Chart 1: Total Sales by Category  
- **Type**: Column Chart  
- **X-Axis**: Category  
- **Y-Axis**: Total Sales  
- **Slicer**: Country
  <img width="902" height="430" alt="image" src="https://github.com/user-attachments/assets/eac69510-bccc-44d8-a3f8-f6ed667f7f8d" />
 

### 📍 Chart 2: Monthly Sales Trend  
- **Type**: Line Chart  
- **X-Axis**: Order Date (Monthly)  
- **Y-Axis**: Total Sales  
- **Slicer**: Category  
<img width="902" height="294" alt="image" src="https://github.com/user-attachments/assets/87c34071-b6ca-4d9e-b382-414734bcd789" />


### 📍 Chart 3: Top 5 Products by Sales  
- **Type**: Bar Chart  
- **Y-Axis**: Product Name  
- **X-Axis**: Total Sales  
- **Filtered**: Top 5 Products  
- **Slicer**: Country  

### 📍 Chart 4: Sales by Payment Method  
- **Type**: Pie Chart  
- **Legend**: Payment Method  
- **Values**: Total Sales  
- **Slicer**: Category  

### 📍 Chart 5: Quantity Sold by Country  
- **Type**: Column Chart  
- **X-Axis**: Country  
- **Y-Axis**: Quantity  
- **Slicer**: Product Name  

### 📍 Chart 6: Sales by Country and Category  
- **Type**: Clustered Column Chart  
- **X-Axis**: Country  
- **Y-Axis**: Total Sales  
- **Legend**: Category  
- **Slicer**: Payment Method  

---

## 🔄 Slicer Functionality

Slicers were added to enhance interactivity and usability. Users can quickly filter the entire dashboard based on:

- **Product Category**
- **Geographical Region (Country)**
- **Preferred Payment Method**

Each selection dynamically updates the relevant charts in real-time.

---

## 📌 Observations & Insights

### 🔹 Total Sales by Category
- **Electronics** is the top-performing category overall (₹149,277.27).
- The **USA** ranks highest in total sales across all categories (₹138,866.54).

### 🔹 Monthly Sales Trend
- Peak sales observed in **June** (₹149,927.42).
- Q2 (May–June) shows strong performance, suggesting seasonal effects or campaigns.

### 🔹 Product-Wise Sales
- **Jackets** (₹37,168.92), **Monitors**, and **Smartphones** are the bestsellers.
- **Socks** surprisingly show high volume, hinting at frequent bulk purchases.

### 🔹 Payment Method Trends
- **Net Banking** (₹143,280.18) leads in payment preference.
- **Digital methods** (Net Banking, PayPal, UPI) account for over **63%** of sales.

### 🔹 Quantity Sold by Country
- **Canada** tops in units sold, indicating high product diversity and engagement.
- **USA** sells fewer units but at higher value, suggesting preference for premium goods.

### 🔹 Sales by Country & Category (w.r.t Payment Method)
- **India** and the **UK** show strong performance via **Net Banking** and **UPI**.
- **PayPal** is widely used in the **USA** and **Australia**.

---

## ✅ Conclusion

The **Online Retail Sales Dashboard** offers a comprehensive visual overview of global retail performance across categories, countries, time periods, and payment preferences.

### Key Takeaways:
- **Electronics** and **Beauty** are the highest revenue contributors.
- The **USA** and **India** are consistently top-performing countries.
- Digital payments dominate, especially **Net Banking** and **UPI**.
- Seasonality impacts sales, with significant spikes in **May and June**.
- The dashboard empowers stakeholders with interactive tools for:
  - **Targeted Marketing**
  - **Inventory Planning**
  - **Customer Preference Analysis**

---

## 📎 Project Files

- 📁 `Online_Retail_Sales_Dashboard.xlsx` — Main Excel file with charts and slicers  
- 📄 `README.md` — Project documentation  
