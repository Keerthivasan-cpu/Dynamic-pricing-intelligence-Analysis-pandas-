# Dynamic-pricing-intelligence-Analysis-pandas-
Dynamic Pricing Intelligence is a Python and Pandas project that analyzes competitor pricing, product sales, discounts, and revenue across multiple e-commerce platforms. It demonstrates data cleaning, data merging, exploratory data analysis (EDA), feature engineering, and business insights through visualizations.

🛒 Dynamic Pricing Intelligence

## 📖 Project Overview

Dynamic Pricing Intelligence is a data analytics project that explores competitor pricing and sales data from multiple e-commerce platforms. The objective is to analyze pricing strategies, compare product prices across platforms, evaluate sales performance, and generate business insights using Python and Pandas.

This project demonstrates the complete data analysis workflow, including data cleaning, merging multiple datasets, exploratory data analysis (EDA), feature engineering, and business-driven insights.

---

# 🎯 Objectives

- Analyze competitor pricing across different e-commerce platforms.
- Compare average product prices by platform.
- Identify the cheapest and most expensive products.
- Evaluate category-wise and brand-wise performance.
- Analyze revenue generated from product sales.
- Understand the impact of pricing on sales.
- Perform data-driven business analysis using Pandas.

---

# 📂 Datasets

The project uses three datasets:

### 1. products.csv
Contains product master information.

**Columns**
- Product ID
- Product Name
- Category
- Brand

---

### 2. competitor_prices.csv
Contains daily competitor pricing information.

**Columns**
- Date
- Product ID
- Platform
- Price
- Discount
- Stock Status

---

### 3. sales.csv
Contains sales transaction records.

**Columns**
- Sale ID
- Date
- Product ID
- Quantity
- Selling Price

---

## 📁 Project Structure

```text
Dynamic-Pricing-Intelligence/
│
├── data/
│   ├── products.csv
│   ├── competitor_prices.csv
│   └── sales.csv
│
├── notebooks/
│   └── Dynamic_Pricing_Analysis.ipynb
│
├── README.md
└── requirements.txt
```

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- google colab

---

# 📊 Data Analysis Workflow

- Import required libraries
- Load datasets
- Explore the data
- Handle missing values
- Check duplicates
- Convert date columns
- Merge multiple datasets
- Perform feature engineering
- Analyze business questions
- Create visualizations
- Generate business insights

---

# 📈 Business Questions Solved

- Which platform offers the lowest average price?
- Which category generates the highest revenue?
- Which products have the highest sales quantity?
- What is the average discount offered by each platform?
- How frequently do products go out of stock?
- Which brand has the highest average product price?

---

# 📌 Key Pandas Concepts Used

- Data Loading (`read_csv`)
- Data Inspection (`head`, `tail`, `info`, `describe`)
- Data Cleaning
- Filtering
- Sorting
- GroupBy
- Aggregation
- Merge
- Feature Engineering
- DateTime Conversion
- Value Counts
- Statistical Analysis
- 
# 🚀 Future Improvements

- Add inventory analysis.
- Predict future product prices using machine learning.
- Build an interactive dashboard using Power BI or Streamlit.
- Automate competitor price monitoring.
- Implement real-time pricing recommendations.

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Merging multiple datasets
- Business data analysis
- Data visualization
- Extracting actionable insights from real-world data
- Applying Pandas for analytical workflows

---

# 👨‍💻 Author

**Keerthivasan**

If you found this project useful, feel free to ⭐ star the repository and share your feedback.

