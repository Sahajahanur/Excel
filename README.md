# 📊 AtliQ Hardware – Sales & Finance Performance Analysis (Excel)

> Excel-based sales analytics for AtliQ Hardware (FY 2019–2021): customer performance, market vs target, and P&L reporting by fiscal year, market and month — to show the business **where growth is coming from and where profit is leaking**.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [What Was Done](#-what-was-done)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [Business KPIs & Expected Impact](#-business-kpis--expected-impact)
- [Reports](#-reports)
- [How to Run This Project](#-how-to-run-this-project)
- [Project Structure](#-project-structure)
- [Limitations & Future Work](#-limitations--future-work)
- [Author & Contact](#-author--contact)

---

## 📌 Overview

This project analyzes AtliQ Hardware's net sales and profitability across three fiscal years (2019–2021). Five Excel-built reports, exported as PDFs, cover customers, markets and P&L statements so that sales and finance teams can monitor performance, track KPIs and plan negotiations.

## ❓ Business Problem

AtliQ Hardware sells through many customers and markets, but leadership lacked one clear view of:

- Which customers are growing and which are declining year over year
- Which markets are meeting or missing sales targets
- How gross margin and net profit change across fiscal years, markets and months

Without this, discounts are set blindly, negotiations lack evidence, and expansion decisions are guesswork.

## 🗂 Dataset

| Item | Detail |
|------|--------|
| Company | AtliQ Hardware (provided as part of the Codebasics learning program) |
| Period | Fiscal Years 2019, 2020, 2021 |
| Granularity | Customer, market, division, month |
| Core measures | Net Sales, Net Sales Growth %, Target, Gross Margin, Net Profit |

> The raw dataset is not stored in this repo. Only the final reports are published.

## 🛠 Tools & Technologies

- **Microsoft Excel** – data preparation, calculations, pivot-based reporting
- **PDF export** – shareable stakeholder reports
- **Git & GitHub** – version control and publishing

## 🔧 What Was Done

1. **Data preparation** – organized sales, customer and market data into an analysis-ready structure
2. **Customer performance** – net sales by customer for 2019, 2020, 2021 with YoY growth (21 vs 20)
3. **Market vs target** – compared actual sales against targets for every market
4. **P&L by fiscal year** – tracked revenue, costs and profit across years
5. **P&L by market** – compared profitability across geographies
6. **P&L by month** – studied monthly revenue trends and cost fluctuations

## 💡 Key Insights

> Replace the placeholders below with the exact numbers from your PDF reports.

- **Customers:** [Top X customers contribute ~__% of net sales; __ customers declined in FY21 vs FY20]
- **Markets:** [__ markets met target; __ missed by more than __%]
- **P&L by year:** [Net sales grew __% from FY19 to FY21; gross margin moved from __% to __%]
- **P&L by month:** [Peak months: __; cost spikes seen in __]

## ✅ Recommendations

- Prioritize account management for top-contributing customers and set recovery plans for declining ones
- Review discounts for customers with high sales but weak margin
- Focus expansion and marketing spend on high-growth, target-beating markets
- Investigate markets missing target, and plan inventory and promotions around peak months

## 🎯 Business KPIs & Expected Impact

| KPI | How this analysis helps |
|-----|------------------------|
| Net Sales Growth % | Pinpoints which customers and markets drive or drag growth |
| Target Achievement % | Highlights markets needing intervention |
| Gross Margin % | Supports data-backed discount decisions |
| Net Profit % | Shows profitability by year, market and month |

**Expected impact:** better-informed discount negotiations and sharper market focus. *No impact figure is claimed here — this is an analysis project with no measured post-implementation results.*

## 📄 Reports

| # | Report | Purpose |
|---|--------|---------|
| 1 | [Customer Performance Report](https://github.com/Sahajahanur/Excel/blob/main/Customer%20Performance%20Report.pdf) | Net sales by customer (2019–2021) and YoY growth |
| 2 | [Market Performance vs Target Report](https://github.com/Sahajahanur/Excel/blob/main/Market%20Performance%20vs%20Target%20Report.pdf) | Actual vs target by market |
| 3 | [P&L Statement by Fiscal Year](https://github.com/Sahajahanur/Excel/blob/main/P%26L%20Statement%20by%20Fiscal%20Year.pdf) | Financial performance across fiscal years |
| 4 | [P&L Statement by Markets](https://github.com/Sahajahanur/Excel/blob/main/P%26L%20Statement%20by%20Markets.pdf) | Profitability across geographies |
| 5 | [P&L Statement by Months](https://github.com/Sahajahanur/Excel/blob/main/P%26L%20Statement%20by%20Months.pdf) | Monthly revenue and cost trends |

## 🚀 How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/Sahajahanur/Excel.git
   ```
2. Open any PDF in the `Reports` section above to view the final output.
3. To reproduce the analysis, load the AtliQ dataset into Excel, build pivot tables by customer, market and month, and apply filters for region, market and division.

## 📁 Project Structure

```
Excel/
├── Customer Performance Report.pdf
├── Market Performance vs Target Report.pdf
├── P&L Statement by Fiscal Year.pdf
├── P&L Statement by Markets.pdf
├── P&L Statement by Months.pdf
└── README.md
```

## 🔭 Limitations & Future Work

- Raw data and the Excel workbook are not included in the repo
- Build an interactive **Power BI** dashboard on the same data
- Add forecasting for next-year sales by market
- Automate report refresh with SQL or Python

## 👤 Author & Contact

**Sahajahanur Rahman Laskar**
📧 connectingsrl@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/sahajahanur-laskar/)
🐙 [GitHub](https://github.com/Sahajahanur)
