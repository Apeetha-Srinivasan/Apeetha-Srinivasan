## Hi there 👋
This project analyzes an Online Retail dataset using Python to uncover sales trends, customer behavior, and business insights.

The goal is to clean the raw data, perform exploratory data analysis (EDA), and generate meaningful insights that can support business decisions.
## Objectives

- Clean and preprocess retail transaction data
- Explore sales performance across countries and time
- Identify customer purchasing patterns
- Find high-value customers
- Discover top-selling products
- Visualize insights using charts

- ## Dataset

The dataset contains online retail transactions including:

- Invoice Number
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## Data Cleaning Performed

- Removed missing values
- Removed duplicate records
- Handled negative quantity values
- Removed rows with invalid pricing (`UnitPrice = 0`)
- Created `Total Price` column
- Converted `InvoiceDate` to datetime format
- Extracted:
  - Day
  - Month
  - Hour
  - Day Type

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Business Insights

### Top Country
Identified the country with the highest number of orders / sales.

### Best Sales Month
Analyzed monthly sales trends to determine the highest-performing month.

### Peak Sales Time
Found the busiest order hours.

### Customer Behavior
Studied purchasing frequency and customer segments.

### High-Value Customers
Identified customers contributing the highest revenue.

### Top Products
Found the best-selling products based on quantity and sales value.

---

## Sample Visualizations

Included:

- Bar charts
- Monthly sales trends
- Peak hour analysis
- Customer distribution
- Top products chart

---

## Project Structure

```bash
Online-Retail/
│
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
<!--
**Apeetha-Srinivasan/Apeetha-Srinivasan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
