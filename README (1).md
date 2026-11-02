# Sales Performance Dashboard (Excel)

An interactive Excel dashboard that analyzes sales by product, place, month and year. Built with PivotTables, PivotCharts, slicers and a date timeline, so every chart can be filtered with one click.

![Dashboard Preview](images/dashboard-preview.png)

---

## Objective
To track overall sales performance, find the best and worst performing products and places, and understand sales trends over time so that business decisions are based on data.

## Dataset
- **Sheet:** `Master Data`
- **Records:** 278 sales transactions
- **Period:** January 2020 – December 2022
- **Columns:** Date, Sales Persons, Products, Place, Price, Units, Amount (`Amount = Price × Units`)
- **Products (6):** 4K LED TVs, LED TVs, Laptops, Mobiles, Speakers, Furniture
- **Places (6):** Bapatla, Chirala, Guntur, Ongole, Tenali, Vijayawada
- **Sales persons (6):** Ramesh, Kiran, Gopi, Mahesh, Ganesh, Prathap

## Key Numbers (all data, no filters)
| Metric | Value |
|---|---|
| Total Amount | ₹11,87,31,893 |
| Total Sales (number of transactions) | 278 |
| Total Units Sold | 7,670 |

## Key Insights
- **Top product by revenue:** Laptops (₹4.87 crore), followed closely by 4K LED TVs (₹4.68 crore).
- **Top place by revenue:** Tenali (₹4.11 crore), far ahead of Guntur (₹1.92 crore).
- **Lowest place by revenue:** Ongole (₹1.04 crore).
- **Yearly trend:** revenue fell from ₹5.17 crore in 2020 to ₹3.42 crore in 2021 and ₹3.28 crore in 2022.
- **Peak month:** July has the highest sales (₹1.81 crore across all years).
- **Lowest revenue products:** LED TVs and Speakers, each under ₹40 lakh.

## Dashboard Components
- KPI cards: Total Amount and Total Sales
- Top 3 Selling Products (column chart)
- Sales by Places (bar chart)
- Sales by Month (line chart)
- Sales by Year (donut chart)
- Bottom 4 Selling Products (bar chart)
- Navigation buttons: Dashboard, Products, Sales, Places

## Slicers and Filters
- Date timeline (quarters)
- Products
- Years
- Months
- Place

## Workbook Structure
| Sheet | Purpose |
|---|---|
| `Master Data` | Raw sales data (source for all PivotTables) |
| `Sheet4` | PivotTables and PivotCharts that feed the dashboard |
| `Dash Board` | Final dashboard with KPIs, charts and slicers |

## Tools & Skills Used
- Microsoft Excel
- PivotTables and PivotCharts
- Slicers and Timeline
- Dashboard design and data visualization

## Project Structure
```
├── Sales_Performance_Dashboard.xlsx   # Excel workbook (data + dashboard)
├── images/
│   └── dashboard-preview.png          # Dashboard screenshot
└── README.md                          # Project documentation
```

## How to Use
1. Download `Sales_Performance_Dashboard.xlsx` and open it in Microsoft Excel.
2. Go to the **Dash Board** sheet.
3. Click the slicers (Years, Months, Place, Products) to filter every chart at once.
4. Use the Date timeline to look at a specific quarter.
5. Click the filter-clear icon on a slicer to reset it.

## Author
**Y. Kalpana**
B.Tech in Computer Science and Engineering, MJR College of Engineering and Technology
Data Analyst | Python · SQL · Power BI · Excel
