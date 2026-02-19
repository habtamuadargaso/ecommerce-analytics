
# 📊 E-Commerce Customer Segmentation & Revenue Analytics

## 🧭 Project Overview

This project performs an end-to-end analysis of an online retail e-commerce dataset.
The goal is to clean raw transactional data, engineer useful business features, and generate insights that can support customer segmentation, revenue analysis, and business decision-making.

This notebook demonstrates practical data-science workflow skills including:

* Data quality inspection
* Data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis (EDA)
* Business-focused visualization
* Preparing data for dashboards and segmentation models

---

## 🎯 Business Objective

Online retail data often contains missing identifiers, invalid transactions, and inconsistent values.
The objective of this project is to:

* Prepare a reliable dataset for customer analytics
* Understand purchasing behavior and revenue distribution
* Enable downstream tasks such as RFM segmentation or dashboard reporting

---

## 🗂 Dataset Description

The dataset contains transactional records from an online retail store.

Typical fields include:

* **InvoiceNo** – Transaction identifier
* **StockCode** – Product code
* **Description** – Product name
* **Quantity** – Number of items purchased
* **InvoiceDate** – Transaction timestamp
* **UnitPrice** – Price per item
* **CustomerID** – Unique customer identifier
* **Country** – Customer location

---

## ⚙️ Project Workflow

### 1️⃣ Data Inspection

* Loaded dataset and examined structure
* Checked data types and summary statistics
* Identified missing values and anomalies

### 2️⃣ Data Cleaning

* Removed rows with missing **CustomerID**
* Removed invalid transactions:

  * Negative quantity (returns)
  * Negative or zero prices
* Ensured consistent numeric formats

### 3️⃣ Feature Engineering

Created new business feature:

* **Revenue = Quantity × UnitPrice**

This allows:

* Revenue-based customer analysis
* Sales trend exploration
* Dashboard-ready metrics

### 4️⃣ Exploratory Data Analysis (EDA)

Performed:

* Distribution analysis of sales values
* Transaction behavior exploration
* Revenue visualization

### 5️⃣ Output Preparation

The cleaned dataset can be used for:

* Customer segmentation (RFM analysis)
* Tableau / Power BI dashboards
* Machine learning models
* Business reporting

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## ▶️ How to Run This Project

1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

2. Install dependencies

```
pip install pandas numpy matplotlib seaborn jupyter
```

3. Place dataset in project folder (example):

```
data/online_retail.csv
```

4. Open notebook

```
jupyter notebook Ecommerce_Project.ipynb
```

5. Run all cells

---

## 📈 Example Use Cases

* Identify high-value customers
* Detect sales trends
* Prepare dashboard metrics
* Build churn or lifetime-value models
* Support marketing segmentation

---

## 🚀 Future Improvements

Possible extensions:

* Perform **RFM customer segmentation**
* Build **customer lifetime value model**
* Add **time-series revenue analysis**
* Deploy **interactive dashboard (Tableau/Streamlit)**

---

## 👤 Author

**Habtamu Dargaso**
Data Scientist | Machine Learning | Analytics

GitHub: https://github.com/habtamuadargaso

---

## ⭐ If you find this project useful

Please consider giving the repository a star — it helps support my data-science portfolio journey.

