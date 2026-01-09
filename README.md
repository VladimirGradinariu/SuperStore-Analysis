📊 SuperStore Sales Analysis
---

 End-to-end data analysis project using SQL and Python to extract business insights from retail sales data.

🎯 Project Overview
This project focuses on analyzing historical sales data from a retail superstore in order to:
- understand revenue and profit trends
- evaluate business performance over time
- identify potential inefficiencies and opportunities for improvement
The analysis follows a complete data analytics workflow, from data preparation and SQL-based KPI analysis to Python-driven exploratory analysis and visualization.

 🗂️ Dataset
- Source: Sample Superstore dataset  
- Records: 10,000 sales transactions  
- Features: 21 columns  
- Time period: 2017  
- Missing values: None  
Each record includes order details, customer and product information, as well as key financial metrics such as sales, profit, quantity, and discount.

---

 🛠️ Tools & Technologies
- Python: pandas, matplotlib  
- SQL: MySQL  
- Jupyter Notebook  
- VS Code 
- Git & GitHub
---

🧪 Analysis Workflow

1️⃣ Data Preparation
- Loaded and validated the dataset
- Converted date columns to proper datetime formats
- Created monthly time features for time-based analysis
- Verified data quality (no missing values)

2️⃣ SQL Analysis
- Computed key business KPIs:
  - Total Revenue
  - Total Profit
  - Number of Orders
  - Average Order Value (AOV)
- Performed monthly aggregation of revenue and profit

3️⃣ Python Analysis & Visualization
- Exploratory Data Analysis (EDA)
- Monthly revenue trend visualization
- Monthly profit trend visualization
- Comparative analysis: Revenue vs Profit

---

📈 Key Metrics
- Total Revenue
- Total Profit
- Number of Orders
- Average Order Value (AOV)
These metrics provide a high-level view of overall business performance.

💡 Key Insights
- Revenue and profit do **not always follow the same trend**
- Profit is significantly more **volatile** than revenue
- Some high-revenue months generate relatively **low profit**, likely due to:
  - aggressive discount strategies
  - unfavorable cost structures
- Monitoring profit alongside revenue is critical for sustainable growth

---

📁 Project Structure
SuperStore-Analysis/
│
├── data/
│   └── superstore.csv
│
├── notebooks/
│   └── 01_eda.ipynb
│
├── sql/
│
├── images/
│   └── monthly_profit.png
│   └──monthly_revenue.png
│   └──monthly_revenue_profit.png
│
└── README.md
