# 🏨 Hotel Booking Analysis Dashboard

*An End-to-End Excel Data Analysis & Interactive Dashboard Project*

**Prepared by:** Fidha Sherin | **Role:** Data Analyst | **Tool:** Microsoft Excel

`Pivot Tables` `Pivot Charts` `Slicers` `KPI Cards` `Conditional Formatting` `Excel Tables` `Formulas`

---

## 📌 Overview

Analyzed a real hotel reservations dataset (**City Hotel** & **Resort Hotel**, 2015–2017) to build an interactive Excel dashboard for booking trends, cancellations, and revenue performance. Started with **119,390 raw rows**, cleaned down to **87,228** analysis-ready bookings, and packaged the findings into a single-screen dashboard that filters live by hotel, month, or year.

## 🎯 Objective

- Clean and standardize the raw dataset into a reliable table
- Engineer key fields (Total Nights, Total Guests, Arrival Date, Estimated Revenue, Cancellation Status)
- Build PivotTables covering bookings, cancellations, revenue, ADR, and seasonality
- Design an interactive dashboard with KPI cards, PivotCharts, and slicers

## 🛠️ Tools & Features Used

Excel Tables · PivotTables (12) · PivotCharts · Slicers · KPI Cards · Conditional Formatting · Formulas (IF, DATE, SUMIFS, COUNTIFS, AVERAGEIFS)

## 🧹 Data Cleaning

Removed duplicates and invalid records (zero guests, unrealistic ADR), handled missing values field-by-field, standardized data types, and converted the range into a structured Excel Table.

| Metric | Before | After |
|---|---|---|
| Records | 119,390 | 87,228 |
| Removed | — | 32,162 (≈27%) |

**Calculated fields added:** Total Nights, Total Guests, Arrival Date, Est Revenue, Cancel Status

## 📊 Dashboard

### Dashboard - Part 1
![Dashboard 1](Dashboard_1.png)

### Dashboard - Part 2
![Dashboard 2](Dashboard_2.png)

| Total Bookings | Cancellation Rate | Est. Revenue | Average ADR | Avg. Lead Time |
|---|---|---|---|---|
| **87,228** | **27.52%** | **$22.97M** | **$106.46** | **79.97 days** |

## 💡 Key Insights

- **City Hotel leads** on both volume (61%) and rate ($111.17 vs $99.06 ADR), driving the larger revenue share ($12.15M vs $10.82M)
- **Seasonal demand** — bookings & ADR peak in August, bottom out in January
- **Online TA is the largest but riskiest channel** — 51,553 bookings but ~35% cancellation rate, vs ~12% for Corporate/Complementary
- **Booking origin is concentrated** in Portugal (27,354), UK (10,423), and France (8,823)
- Transient guests dominate at 71,861 of all bookings

## 📌 Business Recommendations

1. Grow Direct & Corporate bookings — the most reliable channels
2. Reduce cancellations on Online TA through reminders and flexible policies
3. Run targeted campaigns to boost off-season (January) demand
4. Move toward dynamic pricing based on live booking pace
5. Focus marketing spend on top markets: Portugal, UK, France

## 📫 Contact

Fidha Sherin MK — [LinkedIn](https://www.linkedin.com/in/fidhasherinmk/) | fidhasherin37@gmail.com
