# 📊 **Customer Behavior Analysis – End-to-End Data Analytics Project**

## 📝 **Overview**

This project analyzes customer purchasing patterns using an end-to-end Data Analytics workflow.
It covers data loading, EDA, cleaning, SQL insights, and interactive dashboard creation in Power BI, followed by a final business report.

---
## 📂 **Dataset**

* **File:** `customer_orders.csv`
* **Description:** Contains customer order details used to study buying behavior, sales patterns, and performance trends.
* **Stored in:** `/data/` folder

---

## 🛠️ **Tools & Technologies**

* **Python:** Pandas, NumPy, Matplotlib/Seaborn
* **SQL Databases:** PostgreSQL / MySQL / SQL Server
* **Power BI Desktop:** Dashboard & visual insights
* **Gamma App:** Final reporting
* **Git & GitHub:** Version control

---

## 🚀 **Project Steps**

### **1. Data Loading (Python)**

* Loaded `customer_orders.csv`
* Inspected rows, columns, datatypes
* Identified missing values, duplicates, outliers

### **2. Exploratory Data Analysis (EDA)**

* Summary statistics
* Univariate & bivariate visualizations
* Key findings about customer purchase patterns

### **3. Data Cleaning**

* Removed duplicates
* Filled/removed missing values
* Standardized formatting
* Added derived columns for better insights

### **4. SQL Analysis**

Executed SQL queries for deeper analysis:

* Filtering & sorting
* GROUP BY aggregations
* JOIN operations
* Window functions (ranking, running totals)
* Exported SQL views for Power BI

### **5. Power BI Dashboard**

The dashboard includes the following visuals:

* **New Card Chart** (KPIs)
* **Button Slicer**
* **Donut Chart**
* **List Slicer**
* **Clustered Column Chart**
* **Clustered Bar Chart**

Key insights include customer trends, sales contribution, and segment performance.

### **6. Report Creation (Gamma)**

* Final presentation summarizing insights
* Business recommendations included

---

## 📁 **Project Structure**

```
/data
    customer_orders.csv
/notebooks
    EDA.ipynb
    Cleaning.ipynb
/sql
    queries.sql
/powerbi
    customer_behavior_dashboard.pbix
/reports
    gamma_report.pdf
README.md
```

---

## 📈 **Results**

* Clean and analysis-ready dataset
* Identified strong patterns in customer behavior
* Created interactive dashboard for decision-making
* Delivered clear insights through a structured report

---

## ▶️ **How to Run This Project**

### **1. Clone the Repository**

```bash
git clone <https://github.com/Khushi-8076/Customer_Behavior_Analysis>
cd customer_behavior_analysis
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run Jupyter Notebooks**

```bash
jupyter notebook
```

### **4. Execute SQL Queries**

Run `queries.sql` in PostgreSQL/MySQL/SQL Server.

### **5. Open Power BI Dashboard**

Open the `.pbix` file in the `/powerbi` folder.

---

Just upload your dashboard image!

