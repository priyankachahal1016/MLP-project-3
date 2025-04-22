#  E-Commerce Data Analysis & Marketing Insights

##  Objective

The goal of this project is to extract actionable **marketing insights** from transactional e-commerce data to define a strategic **marketing plan** moving forward. Additionally, this project aims to build an **analytical dashboard** to monitor key **business metrics and KPIs**.

---

## Business Goals

### 1. Calculate Invoice Value
For each transaction and item level:


### 2. Perform Detailed Exploratory Data Analysis (EDA)

- Understand how many customers are acquired every month
- Track customer retention on a month-to-month basis
- Compare revenue from existing vs new customers over time
- Assess the impact of discounts on revenue
- Analyze KPIs:
  - Revenue
  - Number of Orders
  - Average Order Value (AOV)
  - Number of Customers (existing/new)
  - Quantity Sold
  - Breakdowns by Category, Week, Day, and Month
- Identify seasonality and sales trends by category, location, and time
- Analyze how sales and order volume vary by day
- Calculate and evaluate:
  - Marketing spend as % of revenue
  - Delivery charges as % of revenue
  - Impact of marketing spend on revenue
- Product-level analysis:
  - Most frequently appearing products
  - Products purchased most based on quantity

---

##  Analysis & Modeling

### 1. Customer Segmentation

- **Heuristic (RFM-based)**: Group customers into Premium, Gold, Silver, and Standard categories
- **Scientific (K-Means Clustering)**: Identify customer profiles for strategic segmentation

### 2. Customer Lifetime Value Prediction (CLV)

- Categorize customers into **Low**, **Medium**, and **High Value**
- Perform classification modeling using revenue-based customer segments

### 3. Cross-Selling Analysis

- Conduct Market Basket Analysis using the **Apriori Algorithm**
- Identify frequently bought together items to support bundling strategies

### 4. Predicting Next Purchase Day

- Segment customers based on expected next visit:
  - 0–30 days
  - 30–60 days
  - 60–90 days
  - 90+ days
- Create a classification model using average time between purchases

### 5. Cohort Analysis

- Identify customer cohorts based on month of acquisition
- Evaluate retention rates and behavior across cohorts

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- mlxtend, apyori (for Market Basket Analysis)
- Seaborn, Matplotlib (Visualizations)
- Jupyter Notebook
- Plotly (Dashboarding)



