
# 📊 Insurance Analytics Dashboard (Power BI)

## 🔍 Project Objective

To create interactive dashboards that help stakeholders in an insurance company monitor key metrics across **policy management** and **branch performance**, enabling **data-driven decisions** in customer segmentation, sales tracking, opportunity management, and operational efficiency.

---

## 💼 Business Questions Answered

### Policy Dashboard
- What is the total number of insurance policies, customers, and claims processed?
- How are policies distributed by gender, age bucket, and marital status?
- What is the trend in premium collection over the years?
- What is the status of claims (approved, pending, denied)?
- What percentage of customers are overdue on premium payments?
- Which policy types are most subscribed?
- How many policies are due to expire this year?

### Branch Dashboard
- How many opportunities were created and how many are still open?
- What is the performance of each Account Executive (A/C Exec) based on number of meetings and invoices?
- What is the distribution of opportunity products across categories (e.g., Marine, Fire, Engineering)?
- What are the top 4 opportunities by revenue?
- What stage in the sales funnel generates the highest revenue?
- Are branch teams meeting their sales targets for new policies, renewals, and cross-sells?

---

## 🛠️ Tools & Technologies Used

- **Power BI** – For dashboard creation and interactive visualizations  
- **DAX (Data Analysis Expressions)** – Used for custom measures and calculations  
- **Power Query** – Data transformation and cleaning  
- **Excel** – For initial data handling and structure  
- **Slicers & Filters** – To enable user-driven interactivity  

---

## 🧩 Dashboard Highlights

### ✅ Policy Dashboard
- **KPIs**: Total Policies (5000), Customers (3148), Claims Amount (251M)
- **Visualizations**:
  - Gender-wise, Age-wise, and Marital Status Policy Count
  - Claim Status Distribution (Approved, Pending, Denied)
  - Policy Expiry Tracker
  - YOY Premium Growth (2014–2024)
  - Payment Status Pie Chart
- **Interactive Filters**: Gender, Marital Status, Policy Type

### ✅ Branch Dashboard
- **KPIs**: Total Opportunities (49), Open Opportunities (44), Yearly Meeting Count
- **Visualizations**:
  - Meetings by A/C Exec
  - Invoices by Type (Cross Sell, New, Renewal)
  - Opportunity Product Distribution (Donut Chart)
  - Top 4 Opportunities by Revenue
  - Stage Funnel by Revenue
- **Filters**: Employee Name, Opportunity Stage, Year Selector

---

## Dashboard
https://github.com/DatawithSandhra/Insurance_Analytics/blob/main/Branch_dashboard.png
---

## 💡 Project Insights & Recommendations

### 📌 From Policy Dashboard
- **Balanced Gender Representation**: Indicates inclusive customer base.
- **Pending Claims (33%)**: Suggests the need for process optimization.
- **YOY Premium Decline in Some Years**: Recommend deep-diving into causes (e.g., economic downturns, policy lapse).
- **Policy Expiry Alert**: 526 policies expiring—suggest proactive renewal campaigns.
- **Overdue Payments (30%)**: Opportunity to implement automated reminders or flexible payment plans.

### 📌 From Branch Dashboard
- **Top Performers Identified**: Abhinav Sharma and Vinay lead in meetings and invoices.
- **Product Group Focus**: Employee Benefits and Fire contribute highest to revenue.
- **Stage Funnel Insight**: Most revenue is concentrated in the "Qualify Opportunity" stage—suggesting improvement potential in later stages.
- **Cross-Sell Lagging**: Underperformance here may need better cross-functional selling strategies or customer education.

---

## ✅ Conclusion

This project demonstrates how Power BI can be used to develop powerful **enterprise-level dashboards** for insurance firms. The dashboards provide real-time visibility into sales, customer behavior, claims, and revenue opportunities. It enables teams to **monitor KPIs**, **analyze performance**, and take **strategic actions** for growth and efficiency.


---

## 📁 Datasets Used

The dashboards are built using structured datasets exported from an internal insurance data system. Key datasets include:

- **Customer Information** – Includes demographic details such as gender, age, marital status, etc.
- **Policy Details** – Information on policy type, issue/expiry dates, premium amounts, etc.
- **Claims** – Claim records including status, amount, and approval details.
- **Payment History** – Payment status data such as paid, pending, and overdue.
- **Branch Opportunity Data** – Opportunity pipeline information by product and revenue.
- **Meeting and Invoice Logs** – Tracks meetings by A/C executives and invoice generation.

---

## 📂 Project Files

- `Policy_Dashboard.pbix` – Power BI file containing the Policy Analytics Dashboard.
- `Branch_Dashboard.pbix` – Power BI file containing the Branch Opportunity Dashboard.
- `README.md` – Project summary and documentation.
- `*.xlsx` – Excel files used for initial data exploration and transformation (if applicable).
- `Screenshots/` – Folder containing images of dashboards for reference.

---

