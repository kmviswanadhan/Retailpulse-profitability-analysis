# RetailPulse Inc. — Regional Profitability & Demand Analysis

An end-to-end Excel data analytics project investigating why RetailPulse Inc.'s net profit margin declined from 8.2% to 6.5% over eight quarters despite stable revenue — built entirely in Microsoft Excel, from raw data cleaning through forecasting and executive recommendations.

## 🎯 Business Question

Why did net profit margin drop despite stable revenue, and what should leadership do about it?

## 🔍 Key Finding

**86% of all loss-making transactions** came from a single combination — **Electronics sold in the South region** — where discounting ran at **21.7%**, nearly double the company-wide average of 11.2%. This single, targetable segment explains the majority of the company's margin erosion.

## 🛠️ What This Project Demonstrates

- **Data Cleaning**: Resolved inconsistent text formatting, four mixed date formats (without relying on locale-dependent functions), duplicate records, and missing values — each handled with a documented, defensible rule rather than a blanket fix
- **Data Validation**: Identified and corrected 35 transactions with impossible pricing (Cost > Price), preventing a margin-distorting bug from reaching the final analysis
- **Advanced Formulas**: XLOOKUP, nested IF/IFS, AVERAGEIFS, COUNTIFS, SUMPRODUCT
- **PivotTables & PivotCharts**: Interactive, slicer-linked analysis across Region, Category, and time
- **KPI Design**: A defined set of business-relevant metrics tied directly to the original business question
- **Interactive Dashboard**: A single-page, slicer-controlled executive dashboard
- **Forecasting**: Built and compared two Q1 2026 revenue forecasting methods (linear regression vs. seasonally-adjusted), identifying a ~40% overstatement risk in the naive model
- **Business Communication**: Translated findings into three concrete, impact-estimated recommendations for a named stakeholder

## 📁 Repository Contents

| File | Description |
|---|---|
| `RetailPulse_Dashboard_Final.xlsx` | The complete Excel workbook — cleaned data, PivotTables, charts, KPI dashboard, and forecast |
| `RetailPulse_Documentation.docx` | Full project write-up: business context, methodology, findings, and recommendations |
| `Formula_Log.docx` | A complete reference of every formula used, the problem it solved, and why |
| `RetailPulse_Presentation.pptx` | An 8-slide executive summary deck |
| `screenshots/` | Dashboard and chart images for quick preview without opening Excel |

## 📊 Project Highlights

- 6,598 raw transaction rows cleaned and validated down to 6,500 verified records
- 4 evidence-based key findings, each traced back to a specific, reproducible formula
- 3 strategic recommendations with estimated business impact
- A fully interactive dashboard — no static screenshots required to explore the data

## 🧠 What I Learned

This project was as much about **judgment** as it was about formulas: deciding how to handle missing data without fabricating it, distinguishing a genuine business signal from a data entry error, recovering from a real mid-project data-loss mistake without hiding it, and choosing a forecasting method based on evidence rather than defaulting to the first formula that worked. The full reasoning behind every decision is documented in `RetailPulse_Documentation.docx`.

## 📬 Contact

Feel free to connect or reach out with questions about the methodology or findings.
