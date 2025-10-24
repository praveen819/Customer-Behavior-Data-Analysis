# 🛍️ **Customer Shopping Behavior – End-to-End Data Analytics Project**

---

## 🧩 **Overview**
This project explores **customer shopping behavior** using a dataset containing demographic details, purchase history, and preferences.  
It demonstrates a complete **data analytics pipeline** — from Python-based EDA to SQL analytics and **Power BI dashboarding** — culminating in a business insights report.  

🎯 **Objective:** Understand customer segments, spending patterns, and factors driving revenue growth.  
🧠 **Key Skills:** Data Wrangling | SQL | Visualization | Power BI | Reporting | EDA | AIML (Feature Engineering & Clustering)

---

## 📊 **Dataset**

**File:** `customer_shopping_behavior.csv`  
**Rows:** 3,900 | **Columns:** 18  

| Column | Description |
|:--|:--|
| Customer ID | Unique identifier for each customer |
| Age | Age of the customer |
| Gender | Male / Female |
| Item Purchased | Product purchased |
| Category | Product category (Clothing, Footwear, etc.) |
| Purchase Amount (USD) | Transaction value |
| Location | Customer location |
| Review Rating | Product rating |
| Subscription Status | Yes/No |
| Shipping Type | Delivery mode |
| Discount Applied | Whether discount was used |
| Promo Code Used | Yes/No |
| Previous Purchases | Total historical purchases |
| Payment Method | Mode of payment |
| Frequency of Purchases | Weekly / Monthly / etc. |

---

## 🛠️ **Tools & Technologies**

| Area | Tools Used |
|------|-------------|
| **Programming & Analysis** | Python (Anaconda, Jupyter Notebook) |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, SQLAlchemy |
| **Database** | MySQL Server |
| **Visualization** | Power BI |
| **Reporting** | PowerPoint (PPT) |
| **Documentation** | Markdown (README) |
---
## 💻 Tech Stack

![Python](https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54)
![MySQL](https://img.shields.io/badge/MySQL-005C84?logo=mysql&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?logo=power-bi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?logo=plotly&logoColor=blue)
![Seaborn](https://img.shields.io/badge/Seaborn-3F4F75?logo=python&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?logo=microsoft-powerpoint&logoColor=white)

---

## 🧠 **Skills Demonstrated**
✔️ Data Importing and Cleaning  
✔️ Exploratory Data Analysis (EDA)  
✔️ Feature Engineering (Age Grouping, Frequency Mapping)  
✔️ SQL Querying for Business Insights  
✔️ Power BI Dashboard Development  
✔️ Report Writing & Presentation  
✔️ AIML-ready feature preparation  

---

## 🔍 **Project Workflow**

### **1️⃣ Data Loading & Inspection**
- Loaded CSV dataset into Python using `pandas`.  
- Checked structure, missing values, and summary statistics using `.info()`, `.describe()`, `.isnull().sum()`.  

### **2️⃣ Data Cleaning**
- Imputed missing `Review Rating` values with **category-wise median**.  
- Standardized column names to **snake_case**.  
- Dropped redundant `promo_code_used` column.  

### **3️⃣ Feature Engineering**
- Created **Age Groups** using quantile binning: `young_adult`, `adult`, `middle_aged`, `senior`.  
- Created **purchase_frequency_days** by mapping textual frequency values to numeric days.  

### **4️⃣ SQL Integration**
- Pushed cleaned data into **MySQL** using SQLAlchemy.  
- Executed 10 analytical SQL queries answering:
  - Revenue by gender  
  - Avg purchase by shipping type  
  - Top-rated products  
  - Subscription impact  
  - Customer segmentation and loyalty  

### **5️⃣ Power BI Dashboard**
- Connected Power BI to MySQL table.  
- Built visuals for:
  - 💵 **Revenue by Category & Gender**  
  - ⭐ **Top 5 Rated Products**  
  - 🧍 **Customer Segment Distribution**  
  - 🎯 **Discount & Subscription Insights**

### **6️⃣ Reporting**
- Summarized findings in **PowerPoint slides** combining EDA, SQL, and Power BI insights.  

---

## 📈 **Key Insights**
🔹 Subscribed customers spend **~15% more** than non-subscribed ones.  
🔹 **Middle-aged** customers are top revenue contributors.  
🔹 **Clothing** and **Footwear** dominate sales.  
🔹 Over **60% of repeat buyers** are subscribed.  
🔹 Discounts contribute heavily to total revenue.  

---

## 🚀 **How to Run the Project**

```bash
# 1️⃣ Clone this repository
git clone https://github.com/<yourusername>/Customer-Shopping-Behavior-Analysis.git
cd Customer-Shopping-Behavior-Analysis

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Run Jupyter Notebook
jupyter notebook customer_analysis.ipynb

# 4️⃣ Load cleaned data into MySQL
# (Ensure your MySQL server credentials are set correctly)

# 5️⃣ Open Power BI and connect to MySQL database
# Import visuals, analyze, and review dashboard
