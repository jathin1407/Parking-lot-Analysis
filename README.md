
# 🚗 Parking Lot Usage Analytics Dashboard

## 📌 Project Overview

This project analyzes historical parking lot transaction data to uncover usage patterns, forecast future demand, and provide insights to improve operational efficiency. The data was collected from card-based entry and exit transactions across multiple parking lots over several years.

Built using **Power BI**, the dashboard enables stakeholders (like the University of Iowa's Parking & Transportation Department) to monitor lot usage trends, peak times, and user behaviors to make informed decisions on lot assignments and resource planning.

---

## 🧰 Tech Stack

- **Power BI** – Interactive dashboard development and forecasting
- **DAX** – Measures and KPIs for calculations like usage time and duration buckets
- **Power Query** – Data transformation and time table generation
- **Excel / CSV** – Source data: CardTransaction and CardAccessGroupAssignment

---

## 🔍 Dashboard Features

The interactive dashboard includes the following visuals and metrics:

### 🧠 Key KPIs
- **Average Usage Time Per Transaction** (in minutes)
- **Total Overnight Parking Count**

### 📊 Visual Insights

- **Lot Usage by Group Number**: Tree map showing total usage volume by access group.
- **Transactions by Hour**: Bar chart to identify peak entry/exit times.
- **User Parking Duration**: Categorized durations such as `<1 hour`, `1–4 hours`, `8–24 hours`, `Full Day+`.
- **Monthly Transactions & Forecast**: Line chart showing monthly trend with built-in forecast till 2026.
- **Transactions by Weekday**: Pie chart summarizing usage across days of the week.
- **Top 10 Used Cards**: Identifies the most frequent users based on card number.

### 🎛️ Filters

- **Lot Number Selector** – Slicers to explore data per parking lot
- **Date Range Slider** – Allows temporal filtering (e.g., 2021–2025)

> 📷 *Dashboard Preview:*  
> ![Parking Lot Dashboard](https://github.com/jathin1407/Parking-lot-Analysis/blob/main/Dashboard_Screenshot.png)

---

## 📈 Calculations & Measures

The project includes several custom calculations such as:

- **Adjusted Entry/Exit Times**: Handling nulls by defaulting to midnight of entry/exit day
- **Usage Duration (Minutes)**: Using DAX to calculate time between entry and exit
- **Overnight Count**: Number of transactions where the vehicle stayed overnight
- **Forecasting**: Time series forecasting of monthly transaction counts

---

## 💡 Key Takeaways

- Identified peak usage hours and weekday demand variations
- Forecasted monthly demand to support future planning
- Highlighted access group usage distribution for better resource allocation
- Enabled lot-wise, card-wise filtering for granular insights

---
