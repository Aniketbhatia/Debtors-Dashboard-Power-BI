 **Debtors Analytics: Power BI Dashboard for Financial Control**
An interactive Power BI dashboard developed to analyze and manage outstanding payments across clients—offering smart visuals, KPI tracking, and actionable insights for finance teams.

**📄 Short Description / Purpose**
The Debtors Dashboard is a user-friendly and performance-optimized Power BI report built to monitor and analyze outstanding amounts, payment statuses, and invoice trends. It enables finance teams to track collections, compare MTD/YTD performance, and identify top defaulters.

**🧰 Tech Stack**
The dashboard was built using the following tools and technologies:

**📊 Power BI Desktop** – Core visualization and analytics platform

**🔄 Power Query** – Data transformation layer for invoice, return, and currency datasets

**🧠 DAX** – Used to build dynamic KPIs (MTD, YTD, PYTD), TopN filtering, and conditional formatting

**🧩 Data Modeling** – Properly structured relationships across clients, invoices, payments, and time dimensions

**📁 File Format** – .pbix for development and .png for previews/screenshots

**📈 Data Source**
**Source:** Internal ERP exports + Finance Data Warehouse
Data includes:
Client Master
Invoice details (with dates, amounts, currency)
Return entries
Payment status & due dates
Currency exchange rates (if applicable)
Time dimension table for MTD/YTD calculations

**🚀 Features / Highlights**
• Business Problem
Finance teams struggle to monitor large volumes of outstanding invoices across clients. Without a consolidated view, identifying payment delays, high-risk accounts, or collection performance becomes manual and inefficient.

**• Goal of the Dashboard**
To create a centralized and dynamic reporting solution that:

Tracks debtors and outstanding balances across clients

Supports timely collections by highlighting overdue invoices

Offers YTD, MTD, and PYTD comparisons for better forecasting

Highlights high-risk clients using TopN and return analysis

**• Walkthrough of Key Visuals**
KPI Cards (Top)
Total Outstanding Amount
MTD Collection
YTD vs PYTD Outstanding
Currency-adjusted totals
Outstanding Map View with Tooltips
Geo-visual of outstanding amount by region
Hover tooltips showing client-wise dues
TopN Outstanding Clients
Dynamic bar chart showing Top 5/10/20 clients
Toggle feature to adjust depth of analysis
Status Dashboard with Filters
Outstanding Aging: 0–30, 31–60, 61–90, >90 days
Slicer for Payment Status, Business Units
Invoice & Return Trend Line Charts
Analyze monthly invoice vs return patterns
Spot spikes in return cases or dips in invoicing
Client Transaction Table
Drillable table with client-wise, invoice-wise data
Currency-adjusted values and due dates

**💡 Business Impact & Insights**
📉 Risk Mitigation: Early identification of high outstanding clients improves follow-up strategy

💬 Finance Efficiency: Reduces manual Excel tracking by providing a real-time snapshot

🧮 Performance Tracking: YTD and MTD comparisons help forecast targets and performance

🌍 Multi-Currency Handling: Allows global financial teams to work with accurate local and base currency conversions

📊 C-Suite Ready: Clean, filtered views are ideal for CFOs and Finance Heads during reviews

