# Air-Quality-Index-AQI-Monitoring-Dashboard


### 📌 Project Overview

This project presents an **Air Quality Monitoring Dashboard** created in **Power BI**, powered by real or synthetic data of AQI readings across cities and monitoring stations. The dashboard is designed to track pollution levels, identify hotspots, and monitor air quality trends over time, aiding decision-makers, environmental analysts, and public health researchers.



### 📁 Project Files

| File Name                     | Description                                                                   |
| ----------------------------- | ----------------------------------------------------------------------------- |
| `AQI_Management_Dataset.xlsx` | Contains raw air quality data including AQI values, locations, and pollutants |
| `AQI DB.pbix`                 | Power BI dashboard with pre-configured reports and visualizations             |



### 📊 Dataset Structure

| Column Name       | Description                                                        |
| ----------------- | ------------------------------------------------------------------ |
| Date              | Date of AQI measurement                                            |
| City              | Name of the city where the data is recorded                        |
| Station Name      | Specific AQI monitoring station                                    |
| AQI               | Air Quality Index value                                            |
| AQI Category      | AQI classification (e.g., Good, Moderate, Poor, Very Poor, Severe) |
| PM2.5             | Fine particulate matter level (in µg/m³)                           |
| PM10              | Coarse particulate matter level (in µg/m³)                         |
| NO₂               | Nitrogen Dioxide concentration                                     |
| SO₂               | Sulfur Dioxide concentration                                       |
| CO                | Carbon Monoxide level                                              |
| O₃                | Ozone level                                                        |
| Temperature (°C)  | Ambient temperature                                                |
| Wind Speed (km/h) | Wind speed at the time of recording                                |
| Humidity (%)      | Relative humidity percentage                                       |



### 💡 Dashboard Features

* 🗺️ AQI heatmap by city and station
* 📉 Daily/weekly/monthly AQI trends
* 🧪 Pollutant-specific tracking (PM2.5, PM10, CO, etc.)
* 🌡️ Correlation of weather factors with AQI (e.g., wind, humidity)
* 📊 AQI category breakdown by time and region
* 🚦 Pollution alert zones and severe AQI warning filters



### 🛠️ Tools Used

* **Power BI Desktop (.pbix)**: For building visuals, KPIs, and interactive filters
* **Microsoft Excel (.xlsx)**: Data pre-processing and pollutant formatting
* **DAX**: Calculated fields for AQI averages, pollution spikes, trendlines, etc.



## 📈 Key Insights You Can Derive



### 1. 🏙️ **City-Level Pollution Trends**

* Track AQI changes over time across cities
* Identify consistently polluted cities or seasonal fluctuations



### 2. 🧪 **Pollutant Impact Analysis**

* Discover which pollutants (e.g., PM2.5, NO₂) are contributing most to high AQI
* Measure the correlation between AQI and individual pollutant spikes



### 3. 🌬️ **Weather vs. Pollution**

* Examine how temperature, humidity, or wind affect air quality
* Understand if low wind speed leads to pollution build-up



### 4. 📊 **AQI Category Distribution**

* Determine the number of days in each AQI category (Good, Moderate, Poor, etc.)
* Identify alert days with Severe or Hazardous air quality



### 5. 📅 **Time Series and Seasonality**

* Identify days or months with peak pollution levels
* Track improvements or deteriorations in air quality over time



### 6. ⚠️ **Station Performance & Hotspot Detection**

* Identify stations frequently reporting hazardous AQI
* Detect if sensor location or urban zones correlate with high pollution


