# ☕ Café Sales Analytics Dashboard

### 📋 Overview
This project analyzes café sales data to uncover insights into product performance, payment behavior, and customer preferences.  
The analysis includes data preparation, exploratory data analysis (EDA), and the creation of **interactive dashboards** using **Plotly Dash** and **Jupyter Notebook**.  

> ⚙️ *Note: The dashboard is currently a work in progress.*  
> Further development will include enhanced interactivity, filtering by time range, and trend comparisons.

---

## 📸 Dashboard & Visual Highlights

### 🔹 Sales Dashboard Preview
![Dashboard Screenshot](images/dashboard_preview.png)

### 🔹 Payment Method Distribution
![Payment Method Pie Chart](images/payment_methods.png)

### 🔹 Monthly Sales Trends
![Monthly Sales Line Chart](images/monthly_sales.png)

*(All visuals were generated dynamically using Plotly and hvPlot.)*

---

## 🧠 Executive Summary

The café’s sales data was analyzed to understand customer spending habits, product performance, and payment preferences across multiple locations and time periods.  
Findings reveal consistent sales across product categories, steady monthly growth, and a balanced distribution of payment methods.  

The data shows that while beverages remain the café’s most consistent revenue drivers, other items such as sandwiches and baked goods also contribute significantly, indicating a well-rounded product mix.

---

## 🔎 Insights Deep Dive

### ☕ Product Insights
- **Top-performing items:** Coffee, Sandwiches, and Smoothies contribute most to total revenue.  
- **Lower-performing items:** Cookies and Cakes show moderate but stable sales trends.  
- Seasonal variation appears in beverage sales, with slight increases during warmer months.

### 💳 Payment Method Trends
- Usage across **Digital Wallet (33.6%)**, **Credit Card (33.2%)**, and **Cash (33.2%)** is nearly **equal**.  
- This even split indicates that the café caters to a wide range of customers — from digital-first to cash-based buyers.  
- Encouraging **Digital Wallet adoption** through loyalty rewards could reduce cash handling and speed up transactions.

### 📅 Transaction Trends
- Monthly sales trends show stable revenue with slight fluctuations that may reflect seasonality or promotional campaigns.  
- Most purchases occur **in-store**, with **takeaway sales** showing room for growth through online ordering or delivery options.

### 📍 Location Insights
- In-store sales account for the majority of revenue, while takeaway purchases are fewer but more consistent in pricing.  
- The data suggests potential to expand takeaway offerings or targeted promotions to balance the two channels.

---

## 💡 Recommendations

1. **Encourage Digital Payment Adoption**  
   - Introduce small discounts or loyalty points for Digital Wallet users to simplify transactions.  

2. **Boost Low-performing Items**  
   - Promote items like cookies and cakes through combo deals (e.g., “Coffee + Cake Special”).  

3. **Leverage Seasonal Patterns**  
   - Plan promotions around high-selling months and introduce limited-time seasonal beverages.  

4. **Enhance Dashboard Interactivity**  
   - Add filters for item type, payment method, and location.  
   - Incorporate tooltips and drilldowns for transaction-level insights.  

5. **Expand Data Tracking**  
   - Integrate customer-level metrics (frequency, average spend) for deeper behavior analysis.

---

## 🚀 How to Run the Dashboard

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/cafe-sales-analytics-dashboard.git
   cd cafe-sales-analytics-dashboard
2. Install dependencies
```bash
   pip install -r requirements.txt
```
3.Run the dashboard
- If using Jupyter Notebook:
     python
```
!jupyter notebook
```
If using a .py Dash script:
python app.py
The app will open automatically in your browser at:
http://127.0.0.1:8050/


📌 *Built with curiosity, caffeine, and code.*

