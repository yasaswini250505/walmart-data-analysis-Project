# 🛒 Walmart Sales Data Analysis Project

This Excel-based data analysis project provides an in-depth exploration of Walmart’s historical sales data across multiple stores over a 3-year period (2010–2012). The goal of the project is to derive actionable business insights using data preparation, pivot analysis, visual dashboards, and forecasting techniques — all within Microsoft Excel.

---

## 📂 Project File
- **Filename:** `walmart data project.xlsx`
- **Software Required:** Microsoft Excel 2016 or later (recommended for full pivot table and chart compatibility)

---

## 📁 Sheet Descriptions

### 1. `SalesData`
> This is the main **raw dataset**, containing weekly sales records for multiple Walmart stores.

**Key columns include:**
- `Store`: Store ID (1 to 45)
- `Date`: Date of the weekly sales record
- `Weekly_Sales`: Sales in USD for that store-week
- `Holiday_Flag`: 1 if the week includes a holiday, otherwise 0
- `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`: Environmental/economic factors

**Added columns:**
- `Year`, `Month`, `Week_day`: Derived from the Date column
- `Holiday_Label`: Text label (“Holiday” or “Non-Holiday”) derived from Holiday_Flag

---

### 2. `Sales by Store and Year`
> A pivot table summarizing **total weekly sales for each store** by year (2010, 2011, 2012). Useful for identifying the best and worst performing stores over time.

---

### 3. `Pivot_Monthly`
> Monthly pivot table aggregating sales by month. Allows analysis of **seasonal sales patterns** and helps with **trend spotting**.

---

### 4. `Pivot Holiday Sales`
> This sheet analyzes **holiday impact on sales**. It compares the average sales during holiday vs. non-holiday weeks.

---

### 5. `Pivot_TopStores`
> A ranking of **top-performing stores** based on total revenue. Helps identify high-performing branches.

---

### 6. `Pivot_Fuel Sales`
> Aggregates monthly fuel prices and correlates them with total sales, identifying a **potential inverse relationship** between fuel cost and store performance.

---

### 7. `Dashboard`
> A visual one-page dashboard summarizing the project with:
- Key Performance Indicators (KPIs)
- Pivot charts
- slicers for interactivity
### Dashboard_preview
-[Dashboard](Dashboard.png)

---

### 8. `ForeCast Analysis`
> A forecasting worksheet that uses simple **time-series extrapolation** to predict future sales. It includes:
- Historical weekly sales
- Forecasted values
- Upper & lower confidence bounds

---

## 📊 Key Insights

- Sales are generally **lower during holiday weeks**.
- **Store 1** outperformed others consistently across all three years.
- Monthly analysis shows **seasonal trends**, with peaks during summer months.
- **Fuel price increases** appear to negatively correlate with weekly sales.
- **Unemployment and CPI** are mildly associated with changes in sales, indicating economic sensitivity.

---

## 📈 Tools & Techniques Used

| Tool / Feature           | Description |
|--------------------------|-------------|
| **Excel Table**          | Structured formatting for dynamic analysis |
| **Pivot Tables**         | Sales breakdown by store, time, and features |
| **Pivot Charts**         | Visualization of sales trends |
| **Calculated Columns**   | Month, Year, Holiday Labels, Weekday |
| **Conditional Formatting** | Highlights high/low values and holidays |
| **KPI Cards**            | Key metrics like Total Sales, Avg Sales |
| **Slicers** *(optional)* | Dashboard filtering |
| **Time-Series Forecasting** | Predicting future sales |

---

## 🛠 How to Use

1. Open the Excel file in Microsoft Excel (preferably 2016+).
2. Start with the `SalesData` sheet to view and understand the raw data.
3. Explore Pivot sheets to study summarized trends.
4. Visit the `Dashboard` for visual insights.
5. Check the `ForeCast Analysis` sheet to see sales predictions.
6. Use filters/slicers (if added) for interactive exploration.

---

## 📌 Project Goal

The main goal of this project is to demonstrate how **Excel can be used as a powerful business intelligence tool** — without needing any external tools — by transforming raw data into clear, actionable insights for decision-makers at Walmart.

---

## 📬 Credits

- **Prepared by: G Yasaswini
- **Dataset Source: [Kaggle - Walmaert sales] (https://www.kaggle.com/datasets/yasserh/walmart-dataset)

---

