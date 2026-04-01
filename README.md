# 🛒 Customer Shopping Behavior Analysis

## 📌 Overview
This project focuses on analyzing customer shopping behavior using real-world transactional data. The objective is to uncover insights related to customer preferences, spending patterns, and business performance to support data-driven decision-making.

The project covers the complete data analysis workflow — from data cleaning and exploration to SQL analysis and dashboard visualization.

---

## 📊 Dataset
- Total Records: 3,900+
- Features: 18
- Includes:
  - Customer demographics (Age, Gender, Location)
  - Purchase details (Product, Category, Amount)
  - Behavior data (Discount usage, Frequency, Ratings, Shipping type)

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy) – Data cleaning & EDA  
- **MySQL** – Data analysis using SQL queries  
- **Power BI** – Interactive dashboard creation  
- **Excel** – Initial data handling  
- **Gamma** – Presentation (PPT creation)

---

## 🔄 Project Steps

### 1. Data Loading & Exploration (Python)
- Loaded dataset using Pandas  
- Checked structure using `.info()` and `.describe()`  
- Identified missing values  

### 2. Data Cleaning & Preparation
- Handled missing values using median imputation  
- Standardized column names (snake_case)  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`  
- Removed redundant columns  

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics  
- Studied purchase trends and behavior  
- Identified key patterns in spending and product preferences  

### 4. SQL Analysis (MySQL)
Performed business-focused analysis:
- Revenue contribution by gender  
- Customer segmentation (New, Returning, Loyal)  
- Top products per category  
- Discount usage impact  
- Subscriber vs non-subscriber behavior  
- Shipping type comparison  

### 5. Dashboard Creation (Power BI)
Built an interactive dashboard to visualize:
- Revenue trends  
- Customer segments  
- Product performance  
- Purchase behavior  

### 6. Reporting & Presentation
- Created a detailed project report (DOC format)  
- Developed a presentation using Gamma to explain insights and recommendations  

---

## 📈 Key Results

- Male customers contributed **67.74% of total revenue**, indicating higher purchasing volume compared to female customers.  
- Repeat customers generated significantly more revenue than new customers.  
- Certain products showed high dependency on discounts.  
- Customers using express shipping had higher average purchase value.  
- Subscription users demonstrated stronger engagement and spending patterns.  

---

## 📊 Dashboard
The Power BI dashboard provides a visual summary of:
- Sales performance  
- Customer segmentation  
- Product insights  

*(Add screenshots here for better impact)*

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Load the dataset in Python (Jupyter Notebook / VS Code)  
3. Run data cleaning and EDA scripts  
4. Import cleaned data into MySQL  
5. Execute SQL queries for analysis  
6. Open Power BI file to view dashboard  
7. Refer to the report and presentation for detailed insights  

---

## 💡 Conclusion
This project demonstrates how combining Python, SQL, and Power BI can help extract meaningful insights from raw data and support better business decisions.

---
