# 🪔 Diwali Sales Analysis — Customer & Sales Intelligence

## 📌 Project Overview

This project analyzes Diwali sales transaction data to understand customer purchasing behavior, identify high-value customer segments, and uncover product and geographic trends.

The analysis uses Python-based Exploratory Data Analysis (EDA) to transform raw sales data into actionable insights that can support marketing, customer targeting, and product planning decisions.

---

## 🎯 Business Objective

The primary objective is to answer:

- Who are the most valuable customer segments?
- Which age groups contribute the most sales?
- Which states generate the highest order volume and revenue?
- Which occupations show stronger purchasing behavior?
- Which product categories perform best?
- Which products receive the highest number of orders?
- How can businesses use these insights to improve festive-season marketing?

---

## 📊 Dataset

The original dataset contains:

- **11,251 records**
- **15 columns**

Customer and transaction attributes include:

| Category | Variables |
|---|---|
| Customer | User ID, Name, Gender, Age, Age Group |
| Demographics | Marital Status, State, Zone |
| Customer Profile | Occupation |
| Product | Product ID, Product Category |
| Sales | Orders, Amount |

After data cleaning, the analysis uses **11,239 valid records across 13 columns**.

---

## 🧹 Data Preparation

The following data-quality steps were performed:

1. Loaded the sales dataset using Pandas.
2. Inspected dataset structure and data types.
3. Identified completely empty columns.
4. Removed `Status` and `unnamed1`.
5. Checked missing values.
6. Identified 12 missing values in `Amount`.
7. Removed records where `Amount` was unavailable.
8. Converted `Amount` from float to integer.
9. Renamed `Cust_name` to `Name`.
10. Performed descriptive statistical analysis.

---

## 🛠️ Technology Stack

### Programming
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Environment
- Jupyter Notebook

---

## 🔍 Exploratory Analysis

### 👥 Customer Demographics

Analyzed:

- Gender distribution
- Age distribution
- Age-group purchasing behavior
- Marital status

Female customers account for **7,832 records**, compared with **3,407 male records** in the cleaned dataset.

Female customers also generated approximately **₹74.34M** in recorded sales versus approximately **₹31.91M** from male customers.

---

### 🎂 Age Group Analysis

The analysis compares purchasing behavior across age groups and gender to identify the customer segments contributing most to sales.

The 26–35 age group emerges as a particularly important customer segment.

---

### 📍 Geographic Analysis

Sales and order volume were analyzed by state.

The analysis identifies **Uttar Pradesh as a leading state by both order volume and amount spent**, while also highlighting differences between rankings based on order count versus sales amount.

This distinction is important because a region can generate many orders without necessarily generating the highest revenue per order.

---

### 💼 Occupation Analysis

Customer occupation was analyzed using both:

- Number of customers/orders
- Total amount spent

The notebook identifies IT-related customers as a particularly strong purchasing segment.

---

### 🛍️ Product Category Analysis

Product categories were compared based on sales/order activity.

The analysis identifies:

- Food
- Clothing
- Electronics

as the strongest-selling categories in the dataset.

---

### 🏆 Top Products

The analysis also identifies the **Top 10 products by number of orders**, helping highlight products that could receive additional promotional or inventory attention.

---

# 💡 Key Business Insights

The analysis indicates that the strongest customer profile is concentrated around:

> **Women aged 26–35, particularly from high-performing states and professional segments, with strong demand for Food, Clothing and Electronics.**

The analysis also highlights Uttar Pradesh as a particularly important market and identifies strong purchasing activity among IT-related customers.

---

# 📈 Business Recommendations

Based on the analysis, businesses could:

### 1. 🎯 Focused Customer Marketing

Prioritize marketing campaigns toward the strongest demographic segments rather than using a single campaign for all customers.

### 2. 📍 Regional Campaigns

Increase promotional focus in high-performing states while investigating why lower-performing regions lag behind.

### 3. 🛍️ Category-Based Promotions

Create bundled offers and targeted promotions around high-performing categories such as:

- Food
- Clothing
- Electronics

### 4. 💼 Occupation-Based Targeting

Use occupation-based customer segmentation to develop targeted offers for high-value professional segments.

### 5. 📦 Inventory Planning

Use the top-performing product list to improve festive-season inventory planning and reduce the risk of stock-outs for popular products.

---

# 🚀 Further Analysis

The project can be extended with:

- Customer segmentation
- Average Order Value (AOV)
- Revenue contribution analysis
- Pareto analysis
- Product-category × demographic analysis
- State × category analysis
- Customer-level purchasing frequency
- Revenue concentration analysis
- Statistical testing
- RFM-style customer segmentation
- Interactive Power BI dashboard

---

# 📁 Project Structure

```text
Diwali-Sales-Analysis/
│
├── Analysis of Diwali Sales data.ipynb
├── README.md
└── images/
