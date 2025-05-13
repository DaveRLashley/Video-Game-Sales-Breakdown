# 🎮 Video Game Sales Dashboard (Tableau Project)

This mini project visualizes global video game sales using Tableau. The dataset includes platform, genre, regional sales, and publisher data for over 16,000 titles.

## 📁 Dataset

Source: [Kaggle - Video Game Sales](https://www.kaggle.com/code/mohaiminul101/video-game-sales/input)  
Cleaned to remove missing years/publishers and future anomalies.

## 📊 Visuals

### 🔹 Global Sales by Genre
- Horizontal bar chart showing which genres dominate global video game sales.

### 🔹 Sales by Platform
- Vertical bar chart showing total global sales per platform.

### 🔹 Regional Sales Breakdown
- Stacked bar chart comparing North America, Europe, Japan, and Other regions.

*Other visuals explored (but not included in the dashboard) include sales over time and publisher rankings.*


## 🛠️ Tools Used
- **ChatGPT + Python (Pandas)** – for data cleaning and preparation
- **Tableau** – for data visualization and dashboard creation
- **GitHub** – to host the cleaned dataset, Tableau workbook, and documentation as part of a public portfolio


## 📌 How to Use
- Clone or download this repo
- Open `vgsales_dashboard.twbx` in Tableau Desktop
- Filter by year, genre, platform, or publisher to explore the data

## 📷 Screenshots
_(Add visuals or dashboard snapshots here)_

## 🧼 Data Cleaning Summary
- Removed rows with missing `Year` or `Publisher`
- Converted `Year` to integer
- Removed entries with `Year > 2024`

---
