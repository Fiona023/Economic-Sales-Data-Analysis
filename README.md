## Ecommerce Sales Data Analysis

## 📌 Project Overview
This project analyzes an e-commerce sales dataset to uncover business insights such as top-selling products, customer behavior, revenue trends, and performance indicators.  
The goal is to demonstrate data cleaning and SQL-based analysis for data-driven decision making.

---

## 📊 Dataset
- *Source:* [Kaggle - Amazon Sales Report](https://www.kaggle.com/datasets/mdsazzatsardar/amazonsalesreport)  
- *Format:* CSV file containing order, shipping, and sales details.
- *Note:* Dataset is not uploaded due to size limitations. Please download it from Kaggle to reproduce the results.  

---

## 🔄 Project Workflow
### 1. Data Cleaning & Preprocessing
- Removed unnecessary columns  
- Filled missing values (mode/mean/unknown replacement)  
- Converted date and postal code columns  

### 2. Exploratory Analysis using SQL
- Top 10 Best-Selling Products by Quantity  
- Monthly Revenue Trend  
- Top Customers by Spend  

### 3. Key Performance Indicators (KPIs)
- *Total Revenue*  
- *Average Order Value (AOV)*  
- *Repeat Purchase Rate*  

---

## 📈 Key Insights
- Identified the *top 10 best-selling products* by quantity  
- Observed *monthly revenue growth trends*  
- Highlighted *top customers* contributing the most revenue  
- Calculated:
  - *Total Revenue* = Sum of all sales  
  - *Average Order Value* = Revenue per order  
  - *Repeat Purchase Rate* = % of customers ordering more than once  

---

## 🛠 Technologies Used
- Python (with `sqlite3` module for SQL queries)
- Pandas, NumPy    
- Jupyter Notebook  

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/Fiona023/Ecommerce-Sales-Data-Analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Ecommerce-Sales-Data-Analysis
   ```
3. Install required Python libraries:
   ```bash
   pip install pandas numpy jupyter
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `Ecommerce_Sales_Data_Analysis.ipynb` to start the analysis.

