# 🛍️ Online Retail Sales Analysis & Customer Insights

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an Online Retail dataset to understand sales patterns, customer purchasing behaviour, product performance, and country-wise sales.

The analysis includes data cleaning, feature engineering, statistical analysis, data aggregation, and visualization using Python.

The goal is to extract meaningful **business insights from retail transaction data** and identify key trends that can support data-driven decision making.

---

## 📊 Dataset

The dataset contains retail transactions recorded between **December 2010 and December 2011**.

### Dataset Features

* `InvoiceNo` – Transaction/Invoice number
* `StockCode` – Product code
* `Description` – Product description
* `Quantity` – Number of products purchased
* `InvoiceDate` – Date and time of transaction
* `UnitPrice` – Price per unit
* `CustomerID` – Unique customer identifier
* `Country` – Customer's country

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Excel

---

## 🧹 Data Cleaning

The following data preprocessing steps were performed:

* Checked dataset structure and data types
* Converted `InvoiceDate` to datetime format
* Identified missing values
* Handled missing `CustomerID` and `Description` values
* Removed duplicate records
* Identified and removed invalid negative quantities
* Removed invalid negative prices
* Handled zero unit prices
* Verified the dataset after cleaning

After cleaning, the dataset contained approximately **535K transaction records**.

---

## ⚙️ Feature Engineering

Several new features were created to support further analysis.

### 💰 Total Price

```python
TotalPrice = Quantity × UnitPrice
```

### 📅 Time Features

The following time-based features were extracted:

* Year
* Month
* Day
* Hour
* Day of Week

### 👥 Customer Segmentation

Customers were categorized based on transaction frequency into:

* Low Value
* Medium Value
* High Value

### 🛒 Order Size

Transactions were categorized based on the quantity purchased into:

* Very Low Order
* Low Order
* Medium Order
* High Order
* Very High Order

---

## 📈 Exploratory Data Analysis

The following analyses were performed to identify important sales and customer trends.

### 🌍 Country-wise Analysis

The **United Kingdom** generated the highest number of transactions, with approximately **489K transactions**.

The UK also contributed the largest share of total sales, followed by:

* Netherlands
* EIRE
* Germany
* France

### 📅 Monthly Sales Analysis

Sales increased significantly toward the end of the year.

**November** recorded the highest monthly sales, with approximately **1.49M** in sales, followed by:

* December
* October

### 🕐 Peak Sales Time

Transaction activity was highest during the **late morning and afternoon hours**, with sales activity declining during the evening.

---

## 👥 Customer Behaviour

Customers were analyzed based on their purchasing frequency.

The analysis shows that a large proportion of transactions belong to the **less-frequent customer segment**, while highly frequent customers contribute a significant number of transactions.

---

## 💰 High-Value Customers

Customer **15152** generated approximately **1.6M** in total sales, making them the highest-value customer in the dataset.

Other high-value customers included:

* 14646
* 18102
* 17450
* 14911

Identifying high-value customers can help businesses develop targeted **retention and loyalty strategies**.

---

## 🛒 Top-Selling Products

The top product based on quantity sold was:

**WHITE HANGING HEART T-LIGHT HOLDER**

with approximately **67,845 units sold**.

Other high-performing products included:

* WORLD WAR 2 GLIDERS ASSTD DESIGNS
* JUMBO BAG RED RETROSPOT
* POPCORN HOLDER
* ASSORTED COLOUR BIRD ORNAMENT

---

## 📊 Visualizations

The project includes several visualizations:

* Country-wise transaction analysis
* Monthly sales analysis
* Quantity distribution
* Total price distribution
* Unit price box plot
* Total price box plot
* Customer segment analysis
* Quantity, UnitPrice, and TotalPrice comparison
* Correlation heatmap
* Pairplot
* Peak sales hour analysis
* Top 10 high-value customers
* Top 10 products by quantity sold

---

## 💡 Key Business Insights

### 📈 Sales Insights

* The **United Kingdom** is the dominant market by transaction volume and revenue.
* **November** recorded the highest monthly sales.
* Sales activity is concentrated around the **late morning and afternoon**.
* Sales increase considerably toward the **end of the year**.

### 👥 Customer Insights

* A large number of transactions come from **less-frequent customers**.
* A small group of **high-value customers** contributes significantly to revenue.
* Customer segmentation can support targeted **marketing and retention strategies**.

### 🛍️ Product Insights

* **WHITE HANGING HEART T-LIGHT HOLDER** is the highest-selling product by quantity.
* A relatively small number of products account for a significant portion of product demand.
* Top-selling products can be prioritized for **inventory planning and promotions**.

---

## 📌 Business Recommendations

Based on the analysis:

* Focus on high-value customers through **loyalty programs and personalized offers**.
* Increase marketing efforts before peak sales months, especially **October and November**.
* Maintain sufficient inventory for **high-demand products**.
* Use customer segmentation to create **targeted marketing campaigns**.
* Explore opportunities to increase sales in **international markets** with strong purchasing activity.
* Investigate low-frequency customers and develop strategies to encourage **repeat purchases**.

---

## 🚀 Conclusion

This project demonstrates how **Python-based exploratory data analysis** can be used to transform raw retail transaction data into meaningful business insights.

The analysis provides insights into:

* Customer behaviour
* Product demand
* Sales trends
* Geographic performance
* High-value customers
* Peak purchasing periods

These insights can help businesses improve **inventory planning, customer retention, marketing strategies, and revenue optimization**.

---

## 👩‍💻 Author

**Apeetha Srinivasan**
