# 🛒 End-to-End Customer Behavior Analytics Dashboard

An end-to-end data analytics project built to analyze customer shopping behavior, revenue distribution, purchasing patterns, and sales performance across demographics and regions.

---

## 📊 Business Key Performance Indicators (KPIs)

- **Total Customers:** 3.9K (Total Dataset) | 207 (Filtered Segment)
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
   - Data modeling, custom DAX measures, and interactive visualization layout.

---

## 📐 Data Model & DAX Measures

- **Total Customers:** `Total Customers = DISTINCTCOUNT(customer_shopping_behavior[Customer ID])`
- **Average Purchase Amount:** `Avg Purchase = AVERAGE(customer_shopping_behavior[Purchase Amount (USD)])`
- **Average Review Rating:** `Avg Rating = AVERAGE(customer_shopping_behavior[Review Rating])`
- **Age Group Column:** Binned age segments (`Young Adult`, `Adult`, `Middle-aged`, `Senior`).

---

## 📈 Key Insights & Visualizations

1. **Sales by Category:** Identifies top-performing product categories (Clothing, Accessories, Footwear, Outerwear).
2. **Sales by Age Group:** Evaluates purchase concentration across demographic age segments.
3. **Revenue by Location:** Highlights top revenue-generating geographic regions.
4. **Customers by Payment Method:** Treemap visualization showing preference across Credit Card, PayPal, Venmo, Cash, and Bank Transfer.
5. **Interactive Filters:** Global slicing by Gender and Shipping Type.

---

## 🔗 Live Interactive Dashboard File

- 💾 **Download `.pbix` File:** [Click Here to View/Download Dashboard File](https://drive.google.com/file/d/13u41fyax50DDPuqgCxfxh4zF0ztPgF2j/view?usp=drive_link)
 
---

## 📁 Repository Structure

```text
├── customer_shopping_behavior.csv    # Raw dataset
├── python_mysql_script.py            # MySQL database script
├── Customer_Behavior_Dashboard.pbix  # Power BI dashboard file
├── dashboard_screenshot.png          # Visual preview
└── README.md                         # Project documentation
