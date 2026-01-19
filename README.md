# Banking & Insurance Analytics

## Project Overview  
This Power BI dashboard provides **end-to-end analytical insights** for a banking organization with integrated insurance data. It enables stakeholders to monitor **branch performance, product adoption, customer behavior, transaction trends, and insurance risk exposure** using interactive visuals and KPI-driven reporting.

The solution is built on a **robust data model** combining banking transactions, customer accounts, branch details, product information, and insurance claims. Advanced **DAX measures**, **time intelligence**, and **interactive navigation** are used to support data-driven decision-making in the BFSI domain.

---

## Dashboard Preview – Report Pages  

This Power BI solution consists of **five interactive report pages**, each designed to address a specific business question.  
The images below provide a visual preview of each page.

> 🔹 Replace image paths with actual GitHub paths after uploading screenshots.

---

### 🏠 1. Home Page  

![Home Page Preview](/images/HOME_PAGE.png)

The **Home Page** acts as a central navigation hub, allowing users to seamlessly move between:
- Branch Analysis  
- Product Analysis  
- Insurance Analysis  
- Information Page  

---

### 🏦 2. Branch Analysis Page  

![Branch Analysis Preview](/images/BRANCH_ANALYSIS.png)

The **Branch Analysis Page** evaluates overall banking performance across regions, cities, and branches.

**Key Insights Include:**
- Total Deposits, Withdrawals & Net Cashflow  
- Active Customers & Average Account Balance  
- Regional Net Cashflow & YoY Performance  
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
- Top 5 Products by Revenue  
- Top 5 Products by Transaction Volume  

This page helps identify **top-performing products**, cross-sell opportunities, and customer preferences.

---

### 🛡️ 4. Insurance Analysis Page  

![Insurance Analysis Preview](/images/INSURANCE_ANALYSIS.png)

The **Insurance Analysis Page** evaluates insurance portfolio health and claim risk.

**Key Insights Include:**
- Total Premiums & Total Claim Amount  
- Claim Ratio & Claim Frequency  
- Average Claim Value  
- City-wise Claim Distribution  
- Customer-level Claim Overview  
- Top High-Risk Customers  
- Claim Status Distribution (Settled / Open / Rejected)

This enables proactive **risk monitoring and claim management**.

---

### ℹ️ 5. Information Page  

![Info Page Preview](/images/INFO_PAGE.png)

The **Information Page** documents technical and functional aspects of the dashboard, including:
- Data sources and model design  
- DAX measures and calculations  
- Performance optimization techniques  
- Navigation and interactivity features  
- Security (Row-Level Security – RLS)

---

## Tools Used  

- **Excel** – Source data for banking and insurance datasets  
- **Power BI Desktop** – Data modeling, DAX calculations, and visualization  
- **DAX (Data Analysis Expressions)** – KPIs, time intelligence, and dynamic metrics  
- **Power Query (M Language)** – Data cleaning, transformation, and shaping  

---

## Power BI Techniques Implemented  

| Technique | Usage |
|---------|-------|
| **Calculated Measures (DAX)** | KPIs like Total Deposits, Net Cashflow, Claim Ratio |
| **Time Intelligence** | YoY, YTD, LY comparisons using `DATESYTD`, `SAMEPERIODLASTYEAR` |
| **Interactive Slicers** | Gender, Year, Region, City |
| **Conditional Formatting** | Highlighting high-risk claims and negative net cashflow |
| **Drill-through & Tooltips** | Branch-level and product-level deep dives |
| **Bookmarks & Navigation Buttons** | Page navigation and view toggles |
| **Row-Level Security (RLS)** | Role-based access for branches and regions |

---

## Dashboard Structure  

### 1. **Branch Performance**  
- KPI Cards: Deposits, Withdrawals, Net Cashflow  
- Regional Performance Table  
- City-wise Branch Coverage  
- Risk Exposure by Customer Segment  

### 2. **Product Performance**  
- Revenue by Product Category  
- Transaction Volume Distribution  
- Top Products by Revenue & Transactions  

### 3. **Insurance & Claims**  
- Claims KPIs and Ratios  
- High-Risk Customer Identification  
- Claim Status & City-wise Analysis  

---

## Domain Knowledge (Banking & Insurance)

| Area | Key Concepts |
|------|--------------|
| **Banking** | Deposits, Withdrawals, Net Cashflow, Account Balances |
| **Products** | Loans, Deposits, Insurance, Investments, Credit Cards |
| **Customers** | Segmentation, Activity Status, Risk Exposure |
| **Insurance** | Premiums, Claims, Claim Ratio, Claim Frequency |
| **Risk** | High-risk customers, exposure by segment |

---

## Business Terms Used  

- **Net Cashflow** – Deposits minus Withdrawals  
- **YoY** – Year-over-Year comparison  
- **Claim Ratio** – Claims Paid vs Premium Collected  
- **RLS** – Row-Level Security  
- **Active Customers** – Customers with recent transactions  

---

## Row-Level Security (RLS)

- **Static RLS**: Region / Branch-based data access  
- **Dynamic RLS**: User-driven access using login credentials  

Ensures **secure and compliant data access** aligned with banking governance policies.

---

## Importing Data into Power BI  

Data is sourced from structured Excel files containing:
- Transactions  
- Customer Accounts  
- Branch & City Details  
- Product Master  
- Insurance Premiums & Claims  

Relationships are modeled using a **star schema** to ensure performance and scalability.

---

## Dashboard Navigation  

- **Slicers**: Year, Gender, Region, City  
- **Buttons**: Home, Branch Analysis, Product Analysis, Insurance Analysis  
- **Tooltips**: Contextual insights without page navigation  

---

**Deployment Ready:**  
Publish to **Power BI Service**, configure RLS, and share securely with stakeholders.
