# 📊 Amazon E-Commerce Sales Analysis (EDA Project)

## 🎯 Objective

The objective of this project is to perform an end-to-end Exploratory Data Analysis (EDA) on an Amazon-style e-commerce dataset to understand customer purchasing behavior, analyze sales performance, and extract meaningful insights that support data-driven decision-making.

---

## 🗂️ Dataset Description

The dataset contains approximately **98,640 transaction records** with 20 features, including:

* Order details (OrderID, OrderDate, OrderStatus)
* Customer information (CustomerID, CustomerName)
* Product details (ProductID, ProductName, Category, Brand)
* Sales metrics (Quantity, UnitPrice, Discount, Tax, ShippingCost, TotalAmount)
* Payment methods (Credit Card, Debit Card, UPI, Cash on Delivery, etc.)
* Geographic data (City, State, Country)
* Seller information (SellerID)

This dataset represents realistic Amazon-style e-commerce transactions and enables comprehensive business analysis.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## 📌 Project Workflow

### 📍 Day 1 — Data Understanding & Profiling

The project began with exploring the dataset structure using `.head()`, `.info()`, and `.describe()`. Columns were categorized into numerical, categorical, and date types, and missing value analysis was performed.

The dataset was found to be clean and well-structured, providing a strong foundation for analysis.

---

### 📍 Day 2 — Data Cleaning & Preprocessing

* Corrected data types
* Standardized categorical variables
* Handled outliers using the IQR method
* Checked duplicate records

The cleaned dataset was saved for further use.

---

### 📍 Day 3 — Exploratory Data Analysis (EDA)

* Sales distribution was right-skewed
* Outliers indicated high-value or bulk purchases
* Orders were evenly distributed across categories and cities
* Strong preference for digital payment methods
* Strong positive relationship between quantity and total sales
* Revenue mainly influenced by unit price and quantity

---

### 📍 Day 4 — Time Analysis & Statistical Testing

* Extracted Year, Month, and Day from OrderDate
* Monthly sales showed seasonality
* Yearly sales remained stable

#### Business Observations

* Sales evenly distributed across cities and categories
* Digital payments dominate
* High delivery success rate
* Balanced seller contribution

#### Statistical Tests

* T-Test → No difference in payment spending
* ANOVA → No difference across categories
* Chi-Square → No relationship between payment method and order status

---

## 🔍 Key Findings

* Sales follow a right-skewed distribution
* Most revenue comes from low-value transactions
* Few high-value orders contribute significantly
* Sales are balanced across categories, cities, and sellers
* Digital payments dominate
* Revenue driven by quantity and unit price
* Seasonal trends exist with stable yearly performance

---

## 💡 Insights

The business operates on a **high-volume, low-value model**, where frequent small purchases drive revenue. A small segment of high-value customers contributes disproportionately to total sales.

Customer behavior is consistent across categories and locations, indicating a well-diversified and stable business.

---

## 🚀 Recommendations

* Increase Average Order Value (AOV) through bundling and upselling
* Target high-value customers with loyalty programs
* Promote digital payments with incentives
* Use seasonal trends for campaigns
* Optimize pricing strategies
* Encourage bulk purchasing

---

## ✅ Final Conclusion

This project demonstrates a complete data analysis workflow, from data cleaning to statistical validation.

The analysis reveals that the business is:

* Stable and consistent
* Balanced across categories, cities, and sellers
* Driven by transaction volume
* Strong in operational performance

These insights can help improve pricing strategies, customer engagement, and overall business performance.


