# 🛍️ Customer Shopping Behavior Analysis

### Data Analytics Project | Python • SQL • PostgreSQL • Power BI

Turning customer shopping data into actionable business insights.

---

## 📌 Project Overview

Understanding customer purchasing behavior is essential for improving sales performance, customer satisfaction, and long-term retention.

This project analyzes **3,900 customer purchase records** to investigate purchasing patterns, customer demographics, discount usage, shipping preferences, subscription behavior, product ratings, and customer loyalty.

Using Python, SQL, PostgreSQL, and Power BI, the project follows a data analytics workflow to prepare data, answer business questions, visualize findings, and develop business recommendations.

## 🎯 Business Objectives

* Analyze revenue contribution by gender and age group.
* Identify high-spending customers who use discounts.
* Evaluate product ratings and purchasing patterns.
* Compare average purchase amounts by shipping method.
* Investigate spending differences between subscribers and non-subscribers.
* Identify products with high discount usage.
* Segment customers based on previous purchases.
* Analyze repeat purchasing and subscription behavior.
* Recommend strategies to improve customer retention and revenue.

## 🧰 Tools & Technologies

| Technology       | Application                                  |
| ---------------- | -------------------------------------------- |
| Python           | Data preparation and exploration             |
| Pandas           | Data manipulation and cleaning               |
| Jupyter Notebook | Interactive analysis                         |
| SQL              | Business queries and analytical calculations |
| PostgreSQL       | Database integration and query execution     |
| Power BI         | Interactive dashboards and visualizations    |
| GitHub           | Project documentation and version control    |

## 📂 Dataset Description

The dataset contains **3,900 records and 18 columns**, representing customer shopping behavior.

The dataset includes information about:

* Customer demographics
* Product categories and purchased items
* Purchase amounts
* Discounts and promotional offers
* Shipping methods
* Subscription status
* Previous purchases
* Product review ratings
* Customer purchasing frequency

**Data quality:** The project presentation reports 37 missing values in the Review Rating column.

## 🔄 Project Workflow

### 1. Data Loading and Exploration

* Imported the dataset using Pandas.
* Examined the dataset structure and column information.
* Reviewed summary statistics and missing values.

### 2. Data Cleaning and Preparation

* Identified missing review ratings.
* Applied median imputation to missing review ratings, as documented in the project presentation.
* Prepared the dataset for further analysis.

### 3. Feature Engineering

* Created age groups for demographic analysis.
* Developed customer purchase-frequency features.
* Prepared customer segments based on previous purchase history.

### 4. SQL Analysis with PostgreSQL

* Integrated the data with PostgreSQL.
* Wrote analytical queries to answer business questions.
* Applied aggregation, filtering, conditional logic, subqueries, CTEs, and window functions.

### 5. Power BI Dashboard

* Presented customer shopping patterns using data visualizations.
* Examined revenue, shipping preferences, subscription behavior, product ratings, and customer segments.

### 6. Business Recommendations

* Interpreted the analysis from a business perspective.
* Identified opportunities for targeted marketing, customer retention, and subscription engagement.

## 🔎 SQL Business Questions

The project answers the following 10 questions:

1. **Revenue by Gender:** How does total revenue compare between male and female customers?
2. **High-Value Discount Users:** Which customers use discounts while spending at least the average purchase amount?
3. **Top-Rated Products:** Which five products have the highest average review ratings?
4. **Shipping Analysis:** How do average purchase amounts compare between Standard and Express Shipping?
5. **Subscription Analysis:** How do average spending and total revenue compare between subscribers and non-subscribers?
6. **Discount Rate by Product:** Which five products have the highest percentage of purchases with discounts?
7. **Customer Segmentation:** How many customers belong to the New, Returning, and Loyal segments?
8. **Product Popularity:** What are the top three most purchased products within each category?
9. **Repeat Purchasers:** How do repeat purchasers with more than five previous purchases compare by subscription status?
10. **Revenue by Age Group:** Which age groups contribute the most revenue?

## 📊 Key Business Insights

The following findings are highlighted in the project's presentation. They should be interpreted alongside the final SQL results and dashboard.

### 1. Revenue by Gender

Female customers generate slightly higher total revenue than male customers in the analyzed dataset.

**Business implication:** Explore customer-specific marketing strategies and validate revenue differences before allocating campaign budgets.

### 2. Shipping Preferences

The presentation reports an average purchase amount of approximately **$65 for Express Shipping** and **$58 for Standard Shipping**.

**Business implication:** Investigate whether customer spending patterns differ by shipping preference and whether premium shipping options contribute to the customer experience.

### 3. Subscription Behavior

The presentation highlights spending and revenue differences between subscription groups.

**Business implication:** Evaluate subscription benefits and develop strategies to encourage suitable customers to subscribe.

### 4. Customer Segmentation

Customers are grouped into New, Returning, and Loyal segments based on their previous purchase counts.

The presentation identifies opportunities to move new customers toward repeat purchasing and stronger loyalty.

**Business implication:** Use targeted campaigns, relevant offers, and loyalty programs to encourage repeat purchases.

### 5. Product Ratings

The analysis identifies highly rated products based on average customer review ratings.

**Business implication:** Highlight well-rated products in relevant marketing campaigns and continue monitoring customer feedback.

## 💡 Business Recommendations

| Opportunity            | Recommendation                                                                |
| ---------------------- | ----------------------------------------------------------------------------- |
| Subscription Growth    | Communicate subscription benefits to relevant customer segments.              |
| Customer Retention     | Introduce loyalty rewards and targeted repeat-purchase campaigns.             |
| Marketing Optimization | Focus campaigns on customer groups with demonstrated value.                   |
| Product Strategy       | Use review ratings and purchase patterns to inform product promotions.        |
| Shipping Strategy      | Investigate purchase value and customer preferences across shipping methods.  |
| Discount Effectiveness | Measure whether discounts encourage purchases and support revenue objectives. |

## 📁 Repository Structure

```text
customer-shopping-behavior-analysis/
│
├── customer_shopping_behavior.csv
├── customer_behavior.sql
├── customer_shopping.ipynb
├── customer_behavior_dashboard.pbix
├── Customer-Shopping-Behavior-Analysis.pptx
├── Customer Shopping Behavior Analysis.pdf
├── README.md
└── LICENSE
```

## 🚀 How to Explore the Project

### Prerequisites

* Python and Jupyter Notebook
* Pandas
* PostgreSQL
* Power BI Desktop

### Steps

1. Clone or download this GitHub repository.
2. Review the CSV dataset and explore the Python notebook.
3. Prepare a PostgreSQL table using column names and data types compatible with the SQL queries.
4. Execute the queries in `customer_behavior.sql`.
5. Open `customer_behavior_dashboard.pbix` in Power BI Desktop.
6. Review the PowerPoint presentation and PDF for the analysis and business recommendations.

**Note:** Database connection settings and table creation may need to be configured locally before executing the SQL queries.

## 📈 Future Improvements

* Add a documented Python exploratory data analysis (EDA).
* Include validated SQL result tables and additional KPIs.
* Add dashboard screenshots to improve project accessibility.
* Investigate customer retention and purchase frequency in greater depth.
* Evaluate discount effectiveness and subscription conversion opportunities.
* Improve dashboard interactivity and business reporting.

## 👩‍💻 Author

**Priya Dharshini**

Aspiring Data Analyst

**Skills:** Python | SQL | PostgreSQL | Pandas | Power BI | Data Visualization | Business Analysis

---

*This project demonstrates an end-to-end customer shopping analysis workflow, from data preparation and SQL analysis to dashboard reporting and business recommendations.*
