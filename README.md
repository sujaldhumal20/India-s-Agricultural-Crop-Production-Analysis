# India's Agricultural Crop Production Analysis

## 📌 Project Overview

India's Agricultural Crop Production Analysis is a data analytics and visualization project developed using Tableau.

The project analyzes historical agricultural crop production data in India from **1997–98 to 2020–21**. The analysis focuses on identifying crop production trends, major crops, state-wise and district-wise production, seasonal patterns, and production efficiency.

An interactive Tableau Dashboard and Story were created to make the analysis easier to explore and understand.

---

## 🎯 Objectives

- Analyze agricultural crop production trends over the years.
- Identify the top-producing crops.
- Compare agricultural production across Indian states.
- Analyze production across different seasons.
- Identify high-producing districts.
- Analyze crop production efficiency relative to cultivated area.
- Present insights through interactive Tableau visualizations.
- Integrate the Tableau Dashboard and Story into a Flask web application.

---

## 📊 Dataset

The dataset contains agricultural crop production records from India.

### Dataset Details

- **Records:** 345,407
- **Columns:** 10
- **Time Period:** 1997–98 to 2020–21
- **File Format:** Excel (.xlsx)

### Main Attributes

- State
- District
- Crop
- Year
- Season
- Area
- Area Units
- Production
- Production Units
- Production per Area

The dataset is available in the `data` folder.

---

## 📈 Visualizations

The project contains the following eight visualizations:

1. **Year-wise Crop Production** – Line Chart
2. **Top 10 Crops by Production** – Horizontal Bar Chart
3. **State-wise Agricultural Production** – Horizontal Bar Chart
4. **Season-wise Agricultural Production** – Bar Chart
5. **Agricultural Production by State** – Map
6. **Top 10 Crops by Production Efficiency** – Horizontal Bar Chart
7. **Crop Season Heatmap** – Heatmap
8. **Top 10 Districts by Production** – Horizontal Bar Chart

---

## 📊 Interactive Dashboard

The Tableau Dashboard provides an interactive view of agricultural production data.

### Dashboard Features

- Total Production
- Total Crops
- Total States/Regions
- Years Covered
- State filter
- Crop filter
- Season filter
- Year filter
- Interactive charts and map

---

## 📖 Tableau Story

The project also includes a six-scene Tableau Story:

1. Agricultural Production Overview
2. Geographic Distribution
3. Crop-wise Production Analysis
4. Season-wise Production Patterns
5. State-wise Comparison
6. Year-wise Crop Production

---

## 🌐 Web Integration

The Tableau Dashboard and Story have been integrated into a **Flask web application** using the **Tableau Embedding API v3**.

### Technologies Used

- Python
- Flask
- HTML
- CSS
- Tableau
- Tableau Embedding API v3

The Flask application provides a web interface where users can directly interact with the Tableau Dashboard and Story.

---

## 🗂️ Project Structure

```text
India-s-Agricultural-Crop-Production-Analysis/
│
├── app.py
│
├── templates/
│   └── index.html
│
├── static/
│   └── css/
│       └── style.css
│
├── data/
│   └── India_Agricultural_Crop_Production.xlsx
│
├── documentation/
│
└── India_Agricultural_Crop_Production_Analysis1.twbx
