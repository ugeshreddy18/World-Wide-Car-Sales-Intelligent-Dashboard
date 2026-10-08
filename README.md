# World-Wide-Car-Sales-Intelligent-Dashboard
# 🚗 Worldwide Car Sales Intelligence Dashboard

An interactive **Microsoft Power BI** dashboard that analyzes global car sales performance across countries, brands, vehicle types and years. It turns raw sales data into clear KPIs and visuals so stakeholders can **analyze, compare and discover** where and how the market is moving.

![Dashboard Preview]
<img width="1431" height="797" alt="Final Car Sales Dashboard" src="https://github.com/user-attachments/assets/7cae9dc0-7a1b-42c8-a0a5-75d180c7d834" />


---

## 📌 Project Overview

The goal of this project is to give business users a single place to understand worldwide car sales without digging through raw data. The dashboard answers questions such as:

- Which brands and countries drive the most units sold and revenue?
- How have sales and revenue trended year over year?
- Which vehicle types and regions lead the market?
- How large is the electric vehicle segment compared with non-electric?

Business requirements were gathered first and then converted into a BI solution made up of KPI cards, trend charts, geographic analysis and drill-down filters.

---

## 🎯 Key Features

- **KPI summary cards** for Total Units Sold, Total Revenue, Total Countries, Total Brands, Electric Vehicle Records, Average Price and Average Market Share
- **Interactive filters (slicers)** for Year (2016–2025) and Country, which update every visual at once
- **Geographic analysis** with a map of units sold by country
- **Brand analysis** with Top 5 Brands by units sold and a Market Share by Brand tree map
- **Trend analysis** with Units Sold Over Years and Revenue Over Years line charts
- **Segment analysis** with Vehicle Type Distribution and Electric vs Non-Electric split
- **Regional comparison** of units sold across Asia, Europe and North America
- **Top 10 Countries table** showing units sold, revenue (billion USD) and market share
- **Custom themed design** with a consistent dark layout and accent colors for easy reading

---

## 📊 Dashboard at a Glance

| KPI | Value |
|---|---|
| Total Units Sold | 480M |
| Total Revenue | 26.60K (Billion USD) |
| Total Countries | 8 |
| Total Brands | 20 |
| Electric Vehicle Records | 200 |
| Average Price | 55.24K |
| Average Market Share | 6.25 |

---

## 🔍 Key Insights

- **SUVs are the largest segment**, at about 27% of units sold (131M), followed by Hatchbacks (about 18%) and Pickups (about 18%).
- **Electric vehicles make up about 25% of units sold** (121M), while non-electric vehicles account for about 75% (359M).
- **Tesla and Volkswagen lead the brand ranking** at roughly 25M units each, with Suzuki and Toyota close behind at about 24M.
- **Asia is the largest region** (about 0.22bn units), ahead of Europe (about 0.19bn) and North America (about 0.08bn).
- **Yearly sales stay in a narrow band** of roughly 45M to 50M units, with dips in 2021 and 2024.

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Business Intelligence | Microsoft Power BI Desktop |
| Calculations | DAX (measures, KPIs, calculated columns) |
| Visuals Used | Cards, Donut, Map, Bar, Tree Map, Line, Column, Table, Slicers |

---

## 🧮 DAX & Data Modeling

- Created **DAX measures** for aggregations such as total units sold, total revenue, average price and average market share
- Built **KPIs and calculated columns** to support the cards, segmentation and ranking visuals
- Used **Top N logic** to produce the Top 5 Brands and Top 10 Countries views
- Optimized calculations to keep the report responsive when filters change

---

## 📁 Repository Structure

```
├── Worldwide_Car_Sales_Dashboard.pbix     # Power BI report file
├── Final_Car_Sales_Dashboard.png          # Dashboard screenshot
├── data/                                  # Dataset used in the report
└── README.md
```

---

## ▶️ How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop** (free to download from Microsoft).
3. Use the **Year** and **Country** slicers on the left to filter the dashboard.
4. Click any chart element to cross-highlight related visuals.

---

## 🚀 Future Enhancements

- Add forecasting for units sold and revenue
- Add brand-level drill-through pages
- Publish to Power BI Service with scheduled data refresh
- Add more countries and a price-segment analysis

---

## 👤 Author

**Borra Ugesh Reddy**
📧 borraugesh@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/borra-ugesh-reddy) | [GitHub](https://github.com/ugeshreddy18)

*If you found this project useful, consider giving it a ⭐*

