# 🌍 Air Quality EDA Project

## 📌 Project Overview
Air pollution is one of the most pressing global environmental challenges, directly impacting human health, ecosystems, and climate. Monitoring air quality helps policymakers and environmental agencies make informed decisions to control emissions and protect public health.

In this project, we explore **global air quality datasets** (with a focus on India) to identify pollution trends, seasonal variations, and city/country comparisons. The dataset used is sourced from Kaggle:

➡️ [Air Quality Data in India (Kaggle)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

---

## 🎯 Objectives
This project aims to:
1. Perform **Exploratory Data Analysis (EDA)** on air quality datasets.
2. Identify patterns and trends in **Air Quality Index (AQI)** and pollutants.
3. Compare **cities, regions, and seasons** in terms of air quality.
4. Visualize results with meaningful plots and maps.

---

## 📂 Dataset Description
The Kaggle dataset contains air quality measurements at **city-level** and **station-level**, recorded on an **hourly** and **daily** basis.

Files used:
- `city_day.csv` → City-level daily data
- `city_hour.csv` → City-level hourly data
- `station_day.csv` → Station-level daily data
- `station_hour.csv` → Station-level hourly data
- `stations.csv` → Metadata for monitoring stations

### Key Columns:
- `City`: Name of the city
- `Date`: Date of observation
- `AQI`: Air Quality Index
- Pollutants: `PM2.5`, `PM10`, `NO2`, `SO2`, `O3`, `CO`

---


---

## 📊 Visualizations
The project includes the following visualizations:

- 📉 **Line plot** showing monthly AQI trends for selected cities
![Line plot](Visualization/AQI.2.png)

- 🔥 **Heatmap** showing correlation between pollutants (`PM2.5`, `PM10`, `NO2`, `SO2`, `O3`, `CO`)
![Heatmap](Visualization/AQI.3.png)

- 🏭 **Stacked bar chart** of pollutant contributions across cities
![Bar chart](Visualization/AQI.5.png)


### 🗺 Map Visualization
One of the highlights of this project is the **interactive AQI map** built using Folium. It allows you to explore pollution levels geographically across different Indian cities.
```


  ```
  You can download the file `aqi_map.html` for opening it in any browser for full interactivity.

---

## ⚙️ Tools & Libraries Used
- **Python** 🐍
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Folium/Plotly** – Interactive map visualizations
- **Jupyter Notebook** – Development environment

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/SyedAzib/air-quality-eda.git
   cd air-quality-eda
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india) and place CSV files inside the project folder.
4. Run the notebook:
   ```bash
   jupyter notebook Project_03_EDA_on_Global_Air_Quality(SMIT).ipynb
   ```

---

## 📌 Results & Insights
- Identified the **most polluted cities** and the **cleanest city** on average.
- Found **seasonal variations** in AQI (higher pollution in winter months).
- Observed **strong correlation** between particulate matter (PM2.5 & PM10) and AQI.
- Noted **missing data patterns** in some pollutants.
- Compared **weekend vs weekday pollution trends**.
- Built an **interactive AQI map** for geographic exploration.

---

## 📜 Future Work
- Extend analysis to **global datasets** for cross-country comparison.
- Develop **predictive models** for AQI using machine learning.
- Build an **interactive dashboard** for real-time air quality monitoring.

---

## 👤 Author
- **Syed Azib (SMIT Project)**
- 📧 Contact: azibwaseem0@gmail.com
- 🌐 GitHub: [SyedAzib](https://github.com/SyedAzib)

---

## 📄 License
This project is licensed under the MIT License – feel free to use and modify with attribution.
