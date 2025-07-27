# 🚕 Uber Fares Data Analysis - Power BI Project

This project is part of the **Introduction to Big Data Analytics (INSY 8413)** course at AUCA.  
The goal was to explore and visualize Uber fare data using Python for preprocessing and Power BI for interactive dashboard creation.

---

## 📌 Objective

Analyze the Uber Fares dataset to uncover insights into fare distribution, time-based ride patterns, and other operational metrics, then present them through a fully interactive Power BI dashboard and an analytical report.

---

## 🧰 Tools Used

- 🐍 **Python (Pandas) Using Google Colab** – for data cleaning and feature engineering
- 📊 **Power BI Desktop** – for interactive dashboard creation
- 🗂 **GitHub** – to store and document project files

---

## 📁 Project Structure

├── uber_cleaned.csv # Cleaned dataset with engineered features

├── uber_dashboard.pbix # Power BI dashboard file you can find it here: https://drive.google.com/file/d/1xC9eWAsI-SPftNqsP4dxUCTN-p9_lu7f/view?usp=sharing

├── screenshots/ # Screenshots of the workflow and dashboard

│ ├── data_loading.png

│ ├── feature_engineering.png

│ ├── dashboard_overview.png

│ └── each_visual_chart.png

├── README.md # Project overview and documentation

└── Uber_Report.pdf # Analytical report


---

## 🔎 Dataset Description

- Source: [Uber Fares Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- Columns included:
  - `pickup_datetime`, `fare_amount`, `passenger_count`, `pickup_latitude`, `pickup_longitude`, etc.
- Additional engineered columns:
  - `hour`, `day`, `month`, `weekday`, `year`, `peak_hour`, etc.

---

## 📊 Dashboard Highlights

The Power BI dashboard includes:
- 📈 Fare distribution (histogram & box plot)
- 🕒 Average fare by hour of the day
- 📅 Ride count by weekday and month
- 🟠 Peak vs Off-Peak ride comparisons
- 🌍 Geospatial distribution (if lat/lon included)
- 🔍 Slicers for time and ride type filtering

---

## 🧠 Key Insights

- Fares tend to peak during morning (7–9 AM) and evening (5–7 PM) hours.
- Fridays and Saturdays showed the highest ride volume.
- Peak hours show higher fare averages compared to off-peak.
- Geographic clusters indicate high demand in urban centers.

---

## ✅ Deliverables

- ✅ Cleaned Dataset (`uber_cleaned.csv`)
- ✅ Power BI Dashboard (`uber_dashboard.pbix`)
- ✅ Screenshots folder (`screenshots/`)
- ✅ Final Report (PDF or PowerPoint)
- ✅ GitHub Repository: [Insert GitHub URL here]

---

