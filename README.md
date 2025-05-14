# Data_sci_project
# 🛍️ Customer Purchase Behavior Analysis

This project analyzes customer purchase behavior using e-commerce transaction data. The goal is to extract actionable insights through data cleaning, exploration, and segmentation techniques such as RFM analysis.

---

## 📌 Project Objectives

- Clean and prepare raw sales data.
- Analyze purchasing trends over time.
- Segment customers using RFM (Recency, Frequency, Monetary) analysis.
- Identify top-performing products and countries.
- Detect churn-risk customers.
- Provide data-driven business recommendations.

---

## 🧰 Tools & Technologies

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Jupyter Notebook**: for development and visualization
- **Power BI / Tableau** *(optional)*: for dashboarding
- **Dataset**: [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail) from UCI or synthetic e-commerce sales data

---

## 🧼 Data Cleaning Steps

- Removed null values
- Removed canceled transactions (InvoiceNo starting with 'C')
- Filtered out negative quantity and price
- Created a `TotalAmount` column = Quantity × UnitPrice

---

## 🔍 Key Analyses

### 1. RFM Segmentation
Segmented customers into categories based on their:
- **Recency** (days since last purchase)
- **Frequency** (number of purchases)
- **Monetary** (total spend)

### 2. Sales Trend Analysis
- Monthly revenue trend
- Peak sales periods identified

### 3. Top Products & Countries
- Top 10 products by total revenue
- Countries contributing the most to overall sales

### 4. Churn Risk Detection
- Identified customers inactive for more than 90 days

---

## 📈 Sample Visualizations

- 📊 Line chart: Monthly revenue trends
- 📦 Bar chart: Top 10 products by revenue
- 🌍 Horizontal bar: Top countries by revenue
- 🔳 Heatmap: RFM score segments

---

## 💡 Business Recommendations

- Target high RFM customers with loyalty programs
- Prepare stock and promotions ahead of peak months (Nov–Dec)
- Use cross-selling opportunities based on frequent item pairs
- Focus marketing on top 3 revenue-generating countries

---

## 📁 Files Included

- `customer_purchase_behavior_analysis.ipynb`: Main Jupyter notebook
- `README.md`: Project overview

---

## 👨‍💼 Author

**Akshat Mishra**  
NIT Certified | Data Analyst  
[LinkedIn Profile (https://www.linkedin.com/in/mishraakshat25/)]  
[Email (akshatmishra507@gmail.coml)]

---

## 📬 Contact

If you'd like to collaborate or want a walkthrough of this notebook, feel free to reach out!

