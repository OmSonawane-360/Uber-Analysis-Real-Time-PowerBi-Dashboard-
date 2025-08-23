# 🚖 Uber Trip Analysis Dashboard | Power BI  

A **Power BI project** that analyzes Uber trip data to uncover insights into **bookings, revenue, trip patterns, demand, and efficiency**.  
The dashboard helps stakeholders with **data-driven decision-making** in areas such as pricing, resource allocation, and operational improvements.  

---

## 📑 Table of Contents  
- 🔎 [Overview](#overview)  
- 🎯 [Why This Project](#why-this-project)  
- ✨ [Features](#features)  
- 📊 [Dashboard Pages](#dashboard-pages)  
- 🌐 [Data Source](#data-source)  
- ⚡ [Power BI Implementation](#power-bi-implementation)  
- 🚀 [Getting Started](#getting-started)  
- 🎨 [Enhancements](#enhancements)  
- 🤝 [Contributing](#contributing)  
- 📜 [License](#license)  
- 👤 [Author](#author)  

---

## 🔎 Overview  

This dashboard analyzes **Uber trip data** to provide insights into:  
- 📈 **Booking trends** and revenue generation  
- ⏱️ **Trip efficiency** in terms of distance and duration  
- 🚗 **Vehicle type analysis** and customer preferences  
- 🌍 **Location-based demand** (pickup & drop-off hotspots)  
- 🕒 **Time-based demand** patterns across hours, days, and weeks  

It is divided into **3 interactive pages** for deep-dive analysis.  

---

## 🎯 Why This Project  

✔ Identify **trends** in ride bookings and revenue.  
✔ Analyze **trip efficiency** (distance, time, value).  
✔ Compare **peak vs. off-peak** demand periods.  
✔ Provide insights for **pricing models** and customer satisfaction.  
✔ Help Uber (or similar businesses) in **strategic planning & demand forecasting**.  

---

## ✨ Features  

- 📊 **KPI Cards** – Total Bookings, Revenue, Distance, Avg Trip Time.  
- 🔄 **Dynamic Measure Selector** – Update charts dynamically (Bookings, Value, Distance).  
- ⏰ **Time-based Analysis** – Trends by hour, day, and intervals.  
- 📍 **Location Analysis** – Top pickup/drop-off points, high-demand areas.  
- 🚙 **Vehicle Type Insights** – Preferred vehicles across locations.  
- 📥 **Download Raw Data** – Export in CSV/Excel for external analysis.  
- 🎛️ **Interactive Filters & Slicers** – City, Date, Payment Type, Trip Type.  
- 🧭 **Drill-Through & Tooltips** – Access deeper insights per trip.  

---

## 📊 Dashboard Pages  

### 1️⃣ Overview Analysis  
- KPIs: **Total Bookings, Total Value, Avg Booking Value, Total Distance, Avg Distance, Avg Time**  
- Trends by **payment type, trip type (day/night), vehicle type**  
- Interactive **slicers and tooltips**  

### 2️⃣ Time Analysis  
- Analyze demand by **time of day, weekday vs. weekend**  
- Visuals:  
  - ⏰ **Area Chart** – Bookings per 10-minute intervals  
  - 📅 **Line Chart** – Trends across days (Mon–Sun)  
  - 🔥 **Heatmap** – Bookings by Hour vs. Day  
- Detect **peak vs. off-peak demand**  

### 3️⃣ Detailed Analysis (Grid Tab)  
- **Trip-level insights** – Trip ID, Distance, Time, Fare, Vehicle Type  
- **Drill-through functionality** from other charts  
- **Conditional formatting** for high/low values  
- Bookmark for **View Full Data** mode  

---

## 🌐 Data Source  

- Dataset: **Uber Trip Records** (CSV/Excel format)  
- Fields include:  
  - Trip ID, Pickup Time, Drop-off Time, Distance, Fare Amount, Payment Type  
  - Pickup & Drop-off Locations (IDs mapped to area names)  
  - Surge Fee, Passenger Count, Vehicle Type  

---

## ⚡ Power BI Implementation  

- 📋 **Table & Matrix Visuals** – for KPIs and vehicle type analysis  
- 🎨 **Conditional Formatting** – highlight trends and outliers  
- 🔄 **Sorting & Filtering** – improve user interaction  
- 🔖 **Bookmarks & Buttons** – Clear Filters, View Data, Export Options  
- 🛠️ **Data Model** – handling inactive relationships (Pickup vs. Drop-off)  

---

## 🚀 Getting Started  

### 🛠️ Prerequisites  
- Power BI Desktop (latest version)  
- Uber trip dataset (CSV/Excel)

---

## 🎨 Enhancements
- 📌 Bookmark for Data Details – Show metric definitions & data sources
- 🧹 Clear Filters Button – Reset all slicers in one click
- 📥 Download Data Button – Export trip data to CSV/Excel
- 📊 Drill-Through Analysis – Access trip-level records from aggregated visuals

---

 ## 👤 Author
- 👨‍💻 **om sonawane** 
- 📧 Contact: **ompatil0357@gmail.com**

 ---


## 🖼️ Preview  

![Dashboard Preview](https://github.com/OmSonawane-360/Uber-Analysis-Real-Time-PowerBi-Dashboard-/blob/main/Dashboard%20Preview/Overview_Analysis_Page.png)  


---

![Dashboard Preview](https://github.com/OmSonawane-360/Uber-Analysis-Real-Time-PowerBi-Dashboard-/blob/main/Dashboard%20Preview/Time_Analysis(total%20bookings).png)  


---

![Dashboard Preview](https://github.com/OmSonawane-360/Uber-Analysis-Real-Time-PowerBi-Dashboard-/blob/main/Dashboard%20Preview/Details_page.png)  

