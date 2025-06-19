# 🏏 IPL 2025 Live Dashboard – Power BI Project

A real-time **IPL 2025 Dashboard** built using **Power BI** and live data from the **Cricbuzz API via RapidAPI**. This project delivers dynamic match analytics, player performance tracking, and interactive visualizations for cricket enthusiasts and analysts.

---

## 🚀 Key Features

- **Live Score Updates**  
  Real-time match updates including ball-by-ball commentary, scores, and status.

- **Detailed Team & Player Stats**  
  Comprehensive stats for both batting and bowling teams, with individual player performance.

- **Interactive Visuals**  
  Power BI charts and visuals to analyze runs, wickets, partnerships, economy rate, etc.

- **Dynamic Filtering**  
  Filter by teams, players, innings, match stages, and more for custom data views.

- **Team Logos & Player Images**  
  Integrated team branding and player pictures for a polished, user-friendly dashboard.

- **Real-Time Refresh**  
  Automatically updates as new data is fetched from the API.

---

## ⚙️ Technical Overview

### 🔗 API Integration
- Uses **Cricbuzz API** from RapidAPI
- Handled using Power Query’s `Web.Contents()` function
- Returns JSON containing match info, players, scores, commentary, etc.

### 🧩 Data Transformation
- Performed in **Power Query Editor**
- Expands nested records and tables into structured tabular format
- Steps include: `Record to Table`, `List to Rows`, `Expand Columns`, `Data Types`, and `Renaming`

### 📊 DAX Calculations
- Built with **DAX** measures & calculated columns
- Used for KPIs like:
  - Strike rate
  - Economy rate
  - Run rate
  - Partnership totals
  - Player comparisons
- Used SWITCH, FILTER, CALCULATE, SUMX, etc.

### 🛡️ Error Handling
- API fail-safe using `try...otherwise`
- Prevents dashboard breakage on data fetch errors or incomplete responses

---

## 🧠 How It Works

1. **Dashboard sends API request** with the API key
2. **Live JSON data** is retrieved from Cricbuzz endpoints
3. **Power Query transforms the data** into relational tables
4. **Visuals update** using DAX measures and slicers
5. **Auto-refresh** triggers keep match data current

---

## 📌 Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **RapidAPI (Cricbuzz API)**
- **JSON / REST APIs**

---

## 📷 Screenshots

_Add screenshots of your Power BI report pages here._

---

## 📫 Contact

**Yashvardhan Singh**  
📧 yashvardhan0464693@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/yashvardhan-singh-261343200)

---

## 💡 Notes

> This project is for educational and analytical purposes only. Cricbuzz API access is via [RapidAPI](https://rapidapi.com) and subject to usage limits.

