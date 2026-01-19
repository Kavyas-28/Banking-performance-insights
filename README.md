# Banking & Insurance Analytics

## Project Overview  
This Power BI dashboard provides **end-to-end analytical insights** for a banking organization with integrated insurance data. It enables stakeholders to monitor **branch performance, product adoption, customer behavior, transaction trends, and insurance claim metrics** using interactive visuals and KPI-driven reporting.

The solution is built on a **clean, structured data model** combining banking transactions, customer accounts, branch details, product information, and insurance claims. Core **DAX measures** and **time-based analysis** support data-driven decision-making in the BFSI domain.

---

## Dashboard Preview – Report Pages  

This Power BI solution consists of **five interactive report pages**, each designed to address a specific business question.  
The images below provide a visual preview of each page.



---

### 🏠 1. Home Page  

![Home Page Preview](/images/HOME_PAGE.png)

The **Home Page** acts as a central navigation hub, allowing users to move between:
- Branch Analysis  
- Product Analysis  
- Insurance Analysis  
- Information Page  

---

### 🏦 2. Branch Analysis Page  

![Branch Analysis Preview](/images/BRANCH_ANALYSIS.png)

The **Branch Analysis Page** evaluates banking performance across regions, cities, and branches.

**Key Insights Include:**
- Total Deposits, Withdrawals & Net Cashflow  
- Active Customers & Average Account Balance  
- Regional Net Cashflow & Year-over-Year comparison  
- City-wise Branch Coverage  
- Top Branches by Transaction Volume  
- Risk Exposure by Customer Segment (Retail, SME, Wealth, Corporate)

---

### 📦 3. Product Analysis Page  

![Product Analysis Preview](/images/PRODUCT_ANALYSIS.png)

The **Product Analysis Page** focuses on product performance and customer adoption trends.

**Key Insights Include:**
- Revenue Contribution by Product Category  
- Transaction Distribution across Products  
- Product-wise Transaction & Amount Trends  
- Top Products by Revenue  
- Top Products by Transaction Volume  

This page helps identify **top-performing products** and usage patterns.

---

### 🛡️ 4. Insurance Analysis Page  

![Insurance Analysis Preview](/images/INSURANCE_ANALYSIS.png)

The **Insurance Analysis Page** evaluates insurance portfolio performance and claim behavior.

**Key Insights Include:**
- Total Premiums & Total Claim Amount  
- Claim Ratio & Claim Frequency  
- Average Claim Value  
- City-wise Claim Distribution  
- Customer-level Claim Overview  
- High-risk Claim Exposure  
- Claim Status Distribution (Settled / Open / Rejected)

---

### ℹ️ 5. Information Page  

![Info Page Preview](/images/INFO_PAGE.png)

The **Information Page** provides documentation on:
- Data sources used  
- Data model structure  
- DAX calculations  
- Navigation guidance  

---

## Tools Used  

- **Excel** – Source data for banking and insurance datasets  
- **Power BI Desktop** – Data modeling, DAX calculations, and visualization  
- **DAX (Data Analysis Expressions)** – KPI calculations and time-based metrics  
- **Power Query (M Language)** – Data cleaning and transformation  

---

## Power BI Techniques Implemented  

| Technique | Usage |
|---------|-------|
| **Calculated Measures (DAX)** | KPIs such as Total Deposits, Net Cashflow, Claim Ratio |
| **Time Intelligence** | YoY and YTD analysis using standard DAX functions |
| **Interactive Slicers** | Year, Gender, Region, City |
| **Drill-down** | Region → City level analysis |
| **Cross-filtering** | Visual interaction for contextual analysis |

---

## Dashboard Structure  

### 1. **Branch Performance**  
- KPI Cards: Deposits, Withdrawals, Net Cashflow  
- Regional Performance Table  
- City-wise Branch Coverage  

### 2. **Product Performance**  
- Revenue by Product Category  
- Transaction Volume Distribution  
- Top Products by Revenue & Transactions  

### 3. **Insurance & Claims**  
- Claims KPIs and Ratios  
- Customer-level Claim Analysis  
- Claim Status & City-wise Distribution  

---

## Domain Knowledge (Banking & Insurance)

| Area | Key Concepts |
|------|--------------|
| **Banking** | Deposits, Withdrawals, Net Cashflow, Account Balances |
| **Products** | Loans, Deposits, Insurance, Investments, Credit Cards |
| **Customers** | Activity status, segmentation |
| **Insurance** | Premiums, Claims, Claim Ratio, Claim Frequency |

---

## Business Terms Used  

- **Net Cashflow** – Deposits minus Withdrawals  
- **YoY** – Year-over-Year comparison  
- **Claim Ratio** – Claims Paid vs Premium Collected  
- **Active Customers** – Customers with recent transactions  

---

## Importing Data into Power BI  

Data is sourced from structured Excel files containing:
- Transactions  
- Customer Accounts  
- Branch & City Details  
- Product Master  
- Insurance Premiums & Claims  

Data is cleaned and transformed using **Power Query** and modeled using a **star schema** for analytical reporting.

---

## Dashboard Navigation  

- **Slicers**: Year, Gender, Region, City  
- **Navigation Buttons**: Home, Branch Analysis, Product Analysis, Insurance Analysis  
- **Cross-highlighted visuals** for interactive exploration  

---

**Deployment Ready:**  
Publish to **Power BI Service** and share insights with stakeholders.
