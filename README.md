# BizMetrics – Business Performance & Sales Analysis

## Project Overview
BizMetrics is an Excel-based business performance and sales analysis project that analyses sales data, evaluates profitability, and presents key business insights through an interactive dashboard.

The project uses a dataset of **500 records** and demonstrates data cleaning, validation, business calculations, Pivot Table analysis, and dashboard development in Microsoft Excel.

## Project Objectives
- Analyse overall business sales performance.
- Calculate gross sales, discounts, net sales, costs, and profit.
- Evaluate key performance indicators (KPIs).
- Identify trends and patterns through Pivot Table analysis.
- Present findings through an interactive Excel dashboard.

## Tools & Technologies
- Microsoft Excel (Advanced Excel)
- Excel Formulas
- Pivot Tables and Pivot Charts
- Slicers
- GETPIVOTDATA
- Data Cleaning & Validation

## Dataset
The dataset contains 500 sales records with the following fields:

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date of sale |
| Region | Sales region (e.g., Central, North) |
| Product | Product (e.g., Laptop) |
| Category | Products Category (e.g.,Electronics) |
| Salesperson | Salesperson who made the sale |
| Units_Sold | Units sold |
| Unit Price | Price per unit (₹) |
| Discount_Rate | Discount applied |
| Unit_Cost | Total cost (₹) |

**Data cleaning and validation:** [e.g., removed duplicates, handled blank values, standardised text entries, validated numeric and date fields]

## Calculations

| Metric | Formula |
|---|---|
| Gross Sales | Quantity × Unit Price |
| Discount Amount | Gross Sales × Discount % |
| Net Sales | Gross Sales − Discount Amount |
| Total Cost | Units_Sold * Unit_Cost |
| Profit | Net Sales − Total Cost |

## Project Workflow
1. **Data Preparation:** Reviewed, cleaned, and validated the dataset.
2. **Data Analysis:** Used Excel formulas and Pivot Tables to calculate and analyse business performance metrics.
3. **Data Visualisation:** Created Pivot Charts and KPI cards.
4. **Dashboard Development:** Built an interactive dashboard using Slicers for data exploration.

## Key Features
- 500-record business dataset
- Sales and profitability calculations
- KPI cards for performance monitoring (Net Sales, Profit, Profit Margin %)
- Interactive Pivot Charts
- Slicer-based filtering
- GETPIVOTDATA for dynamic KPI reporting

## Dashboard Preview

## BizMetrics – Business Performance & Sales Analysis

- [View Dashboard](./dashboard.png.png)
- [Download Excel Workbook](./BizMetrics_Dashboard.xlsx.xlsx)

## Key Insights

**Overall Performance**
- Generated **₹4,81,06,598.78** in net sales and **₹88,97,301.88** in profit, an overall profit margin of **18.49%**.

**Regional Performance**
- **Central** was the top region with **₹1,14,55,169.34** in net sales (**23.81%** of total).
- **North** was the lowest at **₹73,59,888.98** (about 15.3% of total), roughly 36% below Central.

**Category Performance**
- **Laptop** led in both net sales (**₹1,94,14,617.72**) and profit (**₹27,59,752.51**), with a **14.21%** profit margin.
- Laptop's margin is below the overall 18.49%, so it drives volume but not the best returns.

**Monthly Trend**
- **June** recorded the highest net sales at **₹64,33,514.35**.
- **April** was the lowest at **₹24,48,265.29**, so June sales were about 2.6x April's.

**Sales Team**
- **Rahul Mehta** generated **₹1,02,55,678.93** in net sales, contributing **21.32%** of the total.

## Business Recommendations
- **Protect Laptop margins:** Laptop contributes about 40% of net sales but only about 31% of profit. Review discounts and costs on this category.
- **Lift North:** Run targeted promotions or study what Central does differently.
- **Plan for seasonality:** Investigate April's dip and consider campaigns or stock planning around it.
- **Reduce dependence on one performer:** One salesperson accounts for over a fifth of sales, so share best practices across the team.

## How to Use
1. Download `BizMetrics_Dashboard.xlsx` from this repository.
2. Open it in Microsoft Excel (2013 or later is required for Slicers).
3. Go to the Dashboard sheet and use the Slicers to filter by [Region / Category / Month / Salesperson].
4. KPI cards and charts update automatically.

## Project Files
- `BizMetrics_Dashboard.xlsx` – Complete Excel workbook containing the project
- `Screenshots/dashboard.png` – Dashboard preview

## Skills Demonstrated
- Data Cleaning and Validation
- Business Performance Analysis
- Sales Analysis
- Data Visualisation
- Excel Reporting
- Dashboard Development

## Conclusion
BizMetrics shows how Microsoft Excel can transform raw business data into meaningful performance metrics and interactive visual reports that support business decision-making.

## Author
**K RAJ KUMAR**
| [Linkedin](https://www.linkedin.com/in/k-raj-kumar-soltaur03/) | [Gmail](luckyrajkumarr10@gmail.com)
