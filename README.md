# Customer-Behavior-Analytics-PowerBI
End-to-end Data Analytics project using Python, MySQL, and Power BI.
# 🛒 End-to-End Customer Behavior Analytics Dashboard

An end-to-end data analytics project built to analyze customer shopping behavior, revenue distribution, purchasing patterns, and sales performance across demographics and regions.

---

## 📊 Business Key Performance Indicators (KPIs)

- **Total Customers:** 3.9K / 2.85K (Filtered)
- **Average Purchase Amount:** ~$59.87
- **Average Review Rating:** 3.75 / 5.0
- **Subscription Rate:** 27% Subscribed | 73% Non-Subscribed

---

## 🛠️ Tech Stack & Workflow

1. **Python (Pandas / Jupyter Notebook):** 
   - Initial Data Cleaning, Normalization, and Exploratory Data Analysis (EDA).
2. **MySQL Database:** 
   - Relational database storage (`customer_shopping_behavior` table).
   - Executed analytical SQL queries to answer critical business questions.
3. **Power BI Desktop:**
   - Connected via `MySQL Connector/NET`.
   - Data modeling, DAX measures, and custom interactive visualization layout.

---

## 📈 Key Insights & Visualizations

1. **Sales by Category:** Identifies top-performing product categories (Clothing, Accessories, Footwear, Outerwear).
2. **Sales by Age Group:** Evaluates purchase concentration across demographic age segments.
3. **Revenue by Location:** Highlights top revenue-generating geographic regions.
4. **Customers by Payment Method:** Treemap visualization showing preference across Credit Card, PayPal, Venmo, Cash, and Bank Transfer.
5. **Interactive Filters:** Global slicing by Gender, Shipping Type, and Subscription Status.

---

## 📁 Repository Structure
├── customer_shopping_behavior.csv    # Raw dataset

├── python_mysql_script.py            # MySQL script

├── Customer_Behavior_Dashboard.pbix  # Power BI dashboard file

├── dashboard_screenshot.png          # Visual preview

└── README.md                         # Project documentation
