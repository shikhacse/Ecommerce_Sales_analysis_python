# 📊 E-commerce Sales Data Analysis and Business Insights

---

## 📚 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an E-commerce sales dataset.  
The primary goal is to **understand customer and sales behavior**, uncover patterns across different product categories and customer segments, and generate **business insights** that can help optimize marketing and sales strategies.

---

## 🔎 Key Objectives

- Analyze how sales vary across product categories and customer segments.
- Investigate the impact of price, discount, and marketing spend on sales performance.
- Identify patterns, trends, and opportunities for business improvement.

---

## 📈 Exploratory Data Analysis (EDA) and Insights

| Chart | Insight |
|:---|:---|
| **Correlation Matrix** | Very weak or no correlation between Price, Discount, Marketing Spend, and Units Sold. |
| **Sales Distribution by Product Category** | Electronics and Sports have slightly higher total sales, but overall sales are fairly balanced across categories. |
| **Price Distribution** | Product prices are spread between $0 and $1000 with no major skewness. |
| **Discount Distribution** | Discounts vary widely, with most between 20%–40%. |
| **Sales by Customer Segment** | Occasional and Regular customers drive most of the sales compared to Premium customers. |
| **Marketing Spend vs Units Sold** | No clear trend; higher marketing spend does not necessarily result in higher units sold. |
| **Sales Trends Over Time** | Sales fluctuate significantly over time without strong seasonality patterns. |
| **Sales Distribution by Product Category and Customer Segment** | Sales are fairly evenly spread across customer segments within each category. |
| **Boxplot of Price by Product Category** | Wide range of prices across all product categories; no category is strictly expensive or cheap. |
| **Pairplot of Numerical Features** | No strong linear relationships among numerical features. |
| **Distribution of Marketing Spend by Customer Segment** | Marketing spend is similar across all customer segments. |
| **Units Sold Over Time by Product Category** | Sales trends for all categories are volatile, with no single category dominating over time. |
| **Discount Distribution by Product Category** | Toys and Fashion tend to offer slightly higher discounts compared to other categories. |

---

## 📋 Key Findings

- 🔵 No strong predictive relationship between available features and Units Sold.
- 🔵 Sales are distributed relatively evenly across different product categories.
- 🔵 Prices and discounts are spread widely, suggesting varied pricing and promotion strategies.
- 🔵 Marketing spend levels do not guarantee higher sales.
- 🔵 No significant seasonality detected in sales over time.

---

## 🛠 Future Opportunities

- Engineer features like **effective price after discount**.
- Introduce **time-based features** (month, holiday seasonality).
- Collect **product-level metadata** (brand popularity, customer ratings).
- Investigate external factors such as **promotional events** or **competitor actions**.

---

## 📂 Tech Stack

- Python
- Pandas
- Seaborn
- Matplotlib

---

## 📑 Project Files

- [Ecommerce_Sales_analysis.ipynb](assets/Ecommerce_Sales_analysis.ipynb) — Main Notebook
- [Ecommerce_Sales_Prediction_Dataset.csv](assets/Ecommerce_Sales_Prediction_Dataset.csv) — Dataset
- [README.md](README.md) — Project Overview and Documentation


