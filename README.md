
# 🧾 Vrinda Store Analysis

_An interactive Excel dashboard that provides a comprehensive overview of sales performance, order trends, customer demographics, and channel insights for data-driven business decisions._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>  
- <a href="#business-problem">Business Problem</a> 
- <a href="#dataset">Dataset</a> 
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a> 
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This  dashboard  analyzes Vrinda Store’s annual sales data to track performance, customer trends, top states, sales channels, and order status and helping the business make better data-driven decisions. 

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Here is the business problem explained in clear points:
- The company has large sales data, but it is difficult to understand performance from raw numbers.
- It is unclear which months generate the highest and lowest sales.
- The business does not know which states contribute the most revenue.
- There is limited visibility into which sales channels (Amazon, Flipkart, Myntra, etc.) perform best.
- The company needs to understand customer behavior based on age and gender.
- High cancellations, returns, and refunds may be affecting profits.
- Without proper analysis, making data-driven decisions for growth becomes challenging.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Multiple CSV files located in `/data/` folder (sales, vrinda, inventory) 
- Summary table created from ingested data and used for analysis 

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Microsoft Excel
- Pivot Tables
- Charts & Graphs
- GitHub 

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
vrinda-store-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
├── Vrinda Store Reports.pdf
│
├── dashboard/                  # Excel Dashboard File
│   └── vrinda_store_dashboard.XLSX
```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

-Removed duplicate records to avoid incorrect calculations.
- Handled missing or blank values to ensure accurate analysis.
- Standardized data formats (dates, text, currency).
- Corrected spelling errors and inconsistent category names.
- Created new calculated columns (Month, Age Group, Total Sales) for better analysis.

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Negative or Zero Values Detected:**
- Checked for zero or negative sales values. 
- Verified if they were valid (returns/refunds) or data errors.

**Outliers Identified:**
- Found unusually high or low sales values.
- Confirmed whether they were real transactions or mistakes. 

**Correlation Analysis:**
- Analyzed the relationship between orders and sales.
- Compared customer segments and channels to find buying patterns.

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Which month generated the highest sales.
2. **Which state contributes the most revenue?
3. **Which sales channel performs best?
4. **What is the relationship between orders and sales?
5. **Which customer segment buys the most?
6. **How do order statuses impact business performance?

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Excel Dashboard shows:
  - Monthly sales and order trends
  - Top performing states by revenue
  - Sales distribution by gender and age group
  - Orders by different sales channels
  - Order status breakdown (Delivered, Cancelled, Returned, Refunded)
  [(https://github.com/vikas-5381/vrinda-store-analysis-excel/blob/main/Vrinda%20Store%20Analysis_snip.png)]

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
[https://github.com/vikas-5381/vrinda-store-analysis-excel]
```
2.Open the tool:
```bash
Open Excel data tool
```
3. Load the CSVs and ingest into database:
```bash
Vrinda Store Data_Set.xlsx
```
4. Create vendor summary table:
```bash
Vrinda Store Data_Set_summary.py
```
5. Open and run notebooks:
   - `Vrinda Store Data Analysis_exl.xlsx`
   - 
---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- DFocus on high-performing states.
- Invest more in top sales channels.
- Target key customer segments.
- Reduce returns and cancellations.
- Boost sales during peak months.
---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Vikas Siddheshware**  
Data Analyst  
📧 Email: vikassiddheshware2001@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/vikas-siddheshware)  

