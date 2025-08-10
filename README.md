# 🌦 Weather and Climate Data – Exploratory Data Analysis (EDA)

![Image](https://github.com/user-attachments/assets/e9437be3-e58f-4d53-a15e-51b88e52ec77)

## 📌 Overview
This project performs an **Exploratory Data Analysis (EDA)** on a weather and climate dataset to uncover trends, relationships, and seasonal variations in meteorological data.  
The analysis covers:
- Temperature distribution  
- Humidity variations across weather conditions  
- Relationships between temperature, dew point, and humidity  
- Seasonal wind speed changes  
- Correlation patterns between numerical weather variables  
- Atmospheric pressure behaviour under different weather conditions  

The aim is to better understand climate behaviour and identify insights useful for weather prediction and environmental studies.

---

## 📂 Dataset
- **Source:** Kaggle 
- **Format:** CSV  
- **Features:**
  - `Date` – Observation date  
  - `Temperature` – Daily average temperature (°C)  
  - `Humidity` – Relative humidity (%)  
  - `Dew Point` – Temperature at which air becomes saturated (°C)  
  - `Wind Speed` – Average daily wind speed (km/h)  
  - `Visibility` – Average daily visibility (km)  
  - `Pressure` – Atmospheric pressure (hPa)  
  - `Weather Condition` – Categorical weather description (Clear, Rain, Snow, etc.)

---

## 🛠 Tools & Libraries
- Python – Core programming language  
- pandas – Data loading and manipulation  
- numpy – Numerical operations  
- matplotlib & seaborn – Data visualisation  
- plotly *(optional)* – Interactive visualisations  
- scipy / statsmodels – Statistical analysis  

---

## 🔍 Analysis Workflow & Insights

### 1. Data Loading & Cleaning
- Converted `Date` column to proper datetime format.
- Fixed incorrect data types and handled missing values.

### 2. Temperature Distribution
- **Insight:** Ranges from **-13.9°C to 23.5°C**, indicating strong seasonal variation.
  <img width="1051" height="677" alt="Image" src="https://github.com/user-attachments/assets/2a1e3b51-f8c8-4c30-aa20-9611d52839e8" />

### 3. Humidity vs Weather Conditions
- **Insight:** **Snow** has highest humidity (92%), while **clear weather** has lower values.
  <img width="1693" height="502" alt="Image" src="https://github.com/user-attachments/assets/fad56d95-d826-4de5-bd34-3e917c109c9c" />

### 4. Temperature & Dew Point Relationship
- **Insight:** Strong positive correlation — higher humidity when the two are close.
  <img width="967" height="837" alt="Image" src="https://github.com/user-attachments/assets/f26a1cba-edbd-44c7-a70a-6d1ea15d891e" />

### 5. Wind Speed by Month
- **Insight:** **January** records highest speeds (up to 33 km/h); other months are moderate.
  <img width="1236" height="677" alt="Image" src="https://github.com/user-attachments/assets/cca6622c-ae4d-45f2-b459-24c40b3f7213" />

### 6. Correlation Analysis
- **Insight:** Temperature & dew point correlate > 0.8; visibility & humidity negatively correlated.
  <img width="886" height="790" alt="Image" src="https://github.com/user-attachments/assets/f1089fa1-4f4e-4556-92e2-566a5b80451b" />

### 7. Atmospheric Pressure & Weather
- Distribution patterns show variations based on weather categories.
  <img width="1692" height="667" alt="Image" src="https://github.com/user-attachments/assets/f0c18bd4-f0b2-4a6c-bf89-a0cfb3d979b8" />

---

## 📊 Example Visualisations
- Histogram – Temperature distribution  
- Boxplot – Humidity by weather condition  
- Scatterplot – Temperature vs Dew Point  
- Line Chart – Monthly wind speed trends  
- Heatmap – Correlation between numerical variables

---

## 🚀 How to Run
1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/weather-climate-eda.git
   cd weather-climate-eda

---
🎓 Data Analyst & BSc IT (Data Science) Student  
💡 Passionate about leveraging data for impactful solutions  
📍 South Africa  

📫 **Connect with me:**
- [LinkedIn](https://www.linkedin.com/in/keneilwe-makgotlho-287b64218)  
- [Portfolio Website](https://kmakgotlho0.wixsite.com/keneilwe-makgotlho) 
