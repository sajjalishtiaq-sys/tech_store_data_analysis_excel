# Tech Store Sales Analysis (Excel)

An interactive Excel dashboard that analyses 2,000 tech store orders to show revenue performance by time, product, sales channel and region.

**Tools:** Microsoft Excel | Pivot Tables | Slicers & Timelines | Dashboard Design

---

## Sales Dashboard

![Sales Dashboard](sales%20dashboard.png)

**KPIs**

| Metric | Value |
|---|---|
| Total Revenue | $2.45M |
| Total Orders | 2,000 |
| Quantity Sold | 5,552 |
| Average Order Value | $1.23K |

The dashboard includes slicers (Product Category, Region, Sales Channel, Customer Type) and timelines (Year, Quarter, Month, Date) so the data can be filtered interactively.

---

## Key Insights

![Sales Key Insights](sales%20key%20insights.png)

- **Computers drive the business:** they earn $1.35M, about 55% of total revenue. Office Supplies are under 1%.
- **Top products:** Gaming Laptop leads at $433K. The top 5 products bring in about 58% of revenue.
- **Best channels:** Online ($792K) and Corporate Sales ($719K). Marketplace is the weakest at $310K.
- **Regions:** North ($562K) and Central ($557K) lead. West is lowest at $421K.
- **Seasonality:** Revenue peaks in November ($274K) and June ($259K) and dips in July ($151K) and May ($154K).

### Recommendations
1. Promote high-value computers and bundle accessories with them.
2. Invest more in Online and Corporate Sales, and review the Marketplace channel.
3. Run targeted campaigns in West and South to close the gap with North.
4. Plan stock and offers around peak months, and add promotions in slow months.

---

## Data

![Sales Data](sales%20data.png)

**Dataset:** 2,000 orders in the "sales data" sheet.

**Columns:** Order ID, Date, Region, Sales Channel, Customer Type, Product Category, Product, Salesperson, Quantity, Unit Price, Discount, Revenue

**Revenue formula:** Quantity × Unit Price × (1 − Discount)

---

## What I Did
1. Cleaned and organised the raw sales data into a table.
2. Calculated the Revenue column.
3. Built pivot tables for revenue by month, region, category, product and sales channel.
4. Created charts and KPI cards.
5. Added slicers and timelines for interactivity.
6. Designed the final dashboard sheet.

---

## Files in This Repository
- `tech store analysis.xlsx` - the full Excel workbook (data, pivot tables, dashboard)
- `sales dashboard.png` - dashboard screenshot
- `sales key insights.png` - key insights screenshot
- `sales data.png` - data screenshot
