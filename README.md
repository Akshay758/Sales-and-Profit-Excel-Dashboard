# 📊 Sales and Profit Dashboard

![Dashboard Preview](Screenshot (62).png)

> An interactive Excel dashboard providing a comprehensive overview of sales performance, profit trends, and customer insights — filterable by category, year, and month.

---

## 🧩 Overview

This Excel-based **Sales and Profit Dashboard** is designed to help business analysts and decision-makers quickly understand revenue and profit dynamics across product categories, time periods, customer segments, and geographies.

Built entirely in Microsoft Excel using **Pivot Tables**, **Slicers**, and **Charts**, it transforms raw transactional data into a visually rich, interactive reporting tool.

---

## ✨ Features

| Feature | Description |
|---|---|
| 💰 **KPI Cards** | At-a-glance Total Sales ($1,928,888) and Total Profit ($247,961) |
| 📅 **Profit by Year** | Grouped bar chart showing profit split across Furniture, Office Supplies & Technology (2021–2024) |
| 🏆 **Top 5 Customers** | Horizontal bar chart ranking customers by profit contribution |
| 🛍️ **Sales by Category** | Funnel-style chart breaking down sales across 17 sub-categories |
| 🗺️ **Sales by State** | U.S. choropleth map visualizing geographic sales distribution |
| 👥 **Customer Count by Year** | Donut chart tracking unique customers year-over-year |
| 📆 **Sales by Month** | Monthly bar chart showing seasonal sales patterns |
| 🔘 **Interactive Slicers** | Filter all visuals simultaneously by **Category**, **Year**, and **Month** |

---

## 🗂️ File Structure

```
Sales and Profit Dashboard Data.xlsx
├── DATA           # Raw transactional data (orders, customers, regions, products)
├── PIVOT TABLE    # Pivot tables powering all dashboard visuals
└── DASHBOARD      # Final interactive dashboard view
```

---

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel 2016 or later (for full slicer and map chart support)
- Enable **Bing Maps** add-in for the Sales by State map visual

### Usage

1. **Clone or download** this repository
2. Open `Sales and Profit Dashboard Data.xlsx` in Microsoft Excel
3. Navigate to the **DASHBOARD** tab
4. Use the **slicers** on the left panel to filter by:
   - 📦 Category (Furniture / Office Supplies / Technology)
   - 📅 Year (2021 / 2022 / 2023 / 2024)
   - 🗓️ Month (Jan – Dec)
5. All charts update automatically based on your slicer selections

---

## 📈 Key Insights (Default View)

- **Phones** are the top-selling sub-category at **$279,464**
- **Tamara Chand** is the most profitable customer with **$8,981** in profit
- **2023** was the strongest year for Technology profits
- Sales peak in **November and December**, indicating strong seasonal demand
- **California** leads in state-level sales at **$390,145**

---

## 🛠️ Built With

- **Microsoft Excel** — Pivot Tables, Slicers, Charts
- **Bing Maps** — Geographic sales visualization
- **Excel Power Pivot** *(optional)* — For advanced data modeling
