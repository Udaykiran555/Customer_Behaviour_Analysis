
#  Customer Behaviour Data Analytics Project

## 📘 Overview
This project analyzes customer behavior data to uncover insights that can help improve decision-making and business strategy.  
It demonstrates the complete **data analytics lifecycle** — from data loading and cleaning to visualization and presentation — using Python, SQL, and Power BI.

---

## 📊 Dataset
- **Name:** Customer Behaviour Dataset  
- **Source:** (Specify the source, e.g., Kaggle / company dataset / collected manually)
- **Description:** The dataset contains demographic details, purchase patterns, and engagement metrics of customers.  
- **Key Columns:** Customer_ID, Gender, Age, Income, Purchase_Frequency, Product_Category, Total_Spending, etc.  

---

## 🛠️ Tools and Technologies
| Tool / Language | Purpose |
|------------------|----------|
| **Python (Jupyter Notebook)** | Data loading, cleaning, and exploratory data analysis (EDA) |
| **PostgreSQL / MySQL / SQL Server** | SQL query execution and database analytics |
| **Power BI** | Interactive dashboard creation and data visualization |
| **Gamma App (AI Presentation Tool)** | Final report and presentation creation |
| **Pandas, NumPy, Matplotlib, Seaborn** | Data manipulation and visualization in Python |

---

## 🔍 Steps and Workflow
1. **Data Loading**  
   - Imported the dataset into Python using Pandas.  
   - Inspected dataset shape, data types, and missing values.

2. **Data Cleaning**  
   - Removed duplicates and handled missing values.  
   - Corrected data types and standardized categorical values.

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distribution of key variables (Age, Income, Spending).  
   - Analyzed correlations and trends in customer behavior.  
   - Identified top-performing product categories and customer segments.

4. **SQL Analysis**  
   - Loaded cleaned data into **PostgreSQL**, **MySQL**, and **SQL Server**.  
   - Executed queries to answer business questions:
     - Most loyal customers by frequency of purchases  
     - Top product categories by revenue  
     - Average spending per income group  
     - Month-wise sales trends

5. **Power BI Dashboard**  
   - Built an interactive dashboard highlighting:
     - Total revenue, customer segmentation, and sales trends  
     - Age and gender insights  
     - Product category contribution  

6. **Report and Presentation**  
   - Summarized findings in an AI-generated **Gamma presentation**.  
   - Reported actionable business insights and recommendations.

---

## 📈 Dashboard Overview
**File:** `customer_project.pbix`  
- Displays real-time insights on customer purchasing behavior.  
- Includes slicers for filtering by demographics, product category, and time.  
- Visuals: Bar charts, KPIs, Pie charts, and Trend lines.

---

## 🧾 Results and Key Insights
- High-income groups contribute over **40% of total revenue**.  
- Customers aged **25–35** are the most active buyers.  
- The **Electronics** and **Fashion** categories dominate in sales volume.  
- Seasonal peaks observed during **Q4** (holiday season).  
- Suggested targeted marketing campaigns for mid-income segments.

---

## 🚀 How to Run the Project
1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/customer-behaviour-analytics.git
   cd customer-behaviour-analytics

📦 Customer-Behaviour-Analytics
 ┣ 📜 customer.ipynb                # Python notebook for EDA and cleaning
 ┣ 📜 project_customer_behaviour.sql # SQL queries for analysis
 ┣ 📜 customer_project.pbix          # Power BI Dashboard
 ┣ 📜 README.md                      # Project documentation
 ┗ 📂 data/                          # (optional) Raw and cleaned datasets

 
💡 Future Enhancements

.Automate data pipeline with Airflow or Power Automate.

.Integrate live SQL connection in Power BI for real-time updates.

.Deploy interactive analytics app using Streamlit or Dash.

👤 Author

Uday Kiran
📧 [udaygandham81@gmail.com]
]


   

