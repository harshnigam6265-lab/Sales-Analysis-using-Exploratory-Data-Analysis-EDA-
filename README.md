# 📊 Sales Analysis using Exploratory Data Analysis (EDA)

A data analysis project that explores sales performance using the **Sample Superstore Dataset**. The project focuses on data cleaning, feature engineering, exploratory analysis, aggregation, and interactive visualization to uncover meaningful business insights.

---

## 🚀 Project Overview

Businesses generate large volumes of sales data every day. Analyzing this historical data can help identify sales trends, profitable product categories, customer behavior, and areas that require business improvement.

This project uses Python-based Exploratory Data Analysis (EDA) to analyze Superstore sales data and answer important business questions such as:

* Which months generate the highest sales?
* Which product categories contribute the most to sales?
* Which sub-categories perform better?
* How does profit change over time?
* What patterns can be identified from historical sales data?
* What insights can support better business decision-making?

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computations
* **Plotly** — Interactive data visualization
* **Google Colab** — Development environment

---

## 📂 Dataset

The project uses the **Sample Superstore Dataset**, which contains historical information related to orders, customers, products, sales, discounts, profits, and shipping.

### Dataset Contains

* Order information
* Customer information
* Product details
* Product categories and sub-categories
* Sales
* Profit
* Discount
* Shipping information
* Order and shipping dates

---

## 🔍 Analysis Performed

The project follows a structured EDA workflow:

### 1. Data Cleaning

The dataset is inspected and cleaned before analysis. This includes checking the structure of the dataset, handling missing values where necessary, identifying duplicate records, and ensuring that the data types are appropriate.

### 2. Date-Time Conversion

Order and shipping date columns are converted into appropriate date-time formats so that time-based analysis can be performed accurately.

### 3. Feature Engineering

Additional features such as **Month**, **Year**, and other date-related attributes are extracted from the original date columns to make trend analysis easier.

### 4. Monthly Sales Analysis

Sales are aggregated by month to identify seasonal patterns and determine which periods generate higher sales.

### 5. Category-Wise Sales Analysis

Sales performance is compared across major product categories to understand which categories contribute the most to overall revenue.

### 6. Sub-Category Analysis

The performance of individual product sub-categories is analyzed to identify high-performing and low-performing product groups.

### 7. Profit Analysis

Profit is analyzed across different time periods and product groups to understand business profitability and identify important trends.

### 8. Interactive Visualization

Plotly is used to create interactive charts that make it easier to explore sales and profit patterns.

---

## 📈 Visualizations

### 1. Monthly Sales Trend

Shows how sales change over time and helps identify seasonal sales patterns.

![Monthly Sales Trend](Images/result1.png)

---

### 2. Sales by Product Category

Compares total sales across different product categories.

![Sales by Product Category](Images/result2.png)

---

### 3. Sub-Category Wise Analysis

Provides a detailed comparison of sales performance across product sub-categories.

![Sub-Category Wise Analysis](Images/result3.png)

---

### 4. Monthly Profit Analysis

Shows changes in profit over time and helps identify periods of stronger or weaker profitability.

![Monthly Profit Analysis](Images/result4.png)

---

## 💡 Key Insights

The analysis helps identify several important business patterns:

* Identified seasonal patterns in monthly sales.
* Compared sales performance across different product categories.
* Analyzed individual sub-category performance.
* Examined monthly profit trends.
* Identified variations in business performance over time.
* Created interactive visualizations for easier interpretation of the data.
* Converted raw sales data into meaningful business insights.

---

## 📁 Project Structure

```text
Sales_Analysis_EDA/
│
├── Sales_Analysis_EDA.ipynb
├── Sample_Superstore.csv
├── README.md
│
└── Images/
    ├── result1.png
    ├── result2.png
    ├── result3.png
    └── result4.png
```

---

## ▶️ How to Run the Project

### Option 1: Google Colab

1. Open the notebook in Google Colab.
2. Upload `Sample_Superstore.csv`.
3. Run the notebook cells sequentially.
4. Explore the generated analysis and visualizations.

### Option 2: Local Environment

Clone the repository:

```bash
git clone https://github.com/rishavjha252005-blip/Sales_Analysis_EDA.git
```

Navigate to the project directory:

```bash
cd Sales_Analysis_EDA
```

Install the required libraries:

```bash
pip install pandas numpy plotly
```

Open the Jupyter Notebook:

```bash
jupyter notebook Sales_Analysis_EDA.ipynb
```

---

## 🔮 Future Scope

The project can be extended further by:

* Building an interactive **Power BI dashboard**.
* Implementing **sales forecasting using Machine Learning**.
* Performing **customer segmentation using RFM Analysis**.
* Developing a **Streamlit web application**.
* Integrating real-time sales data for live analytics.
* Adding advanced profitability and customer-level analysis.

---

## 👨‍💻 Developed By

**Harshit Nigam**
**NIT Raipur**

---

## ⭐ If You Find This Project Useful

Consider giving this repository a ⭐ on GitHub and exploring the notebook to understand the complete analysis workflow.
