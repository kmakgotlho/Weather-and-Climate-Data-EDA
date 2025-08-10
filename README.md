# 🌦 Weather and Climate Data – Exploratory Data Analysis (EDA)

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

### 3. Humidity vs Weather Conditions
- **Insight:** **Snow** has highest humidity (92%), while **clear weather** has lower values.

### 4. Temperature & Dew Point Relationship
- **Insight:** Strong positive correlation — higher humidity when the two are close.

### 5. Wind Speed by Month
- **Insight:** **January** records highest speeds (up to 33 km/h); other months are moderate.

### 6. Correlation Analysis
- **Insight:** Temperature & dew point correlate > 0.8; visibility & humidity negatively correlated.

### 7. Atmospheric Pressure & Weather
- Distribution patterns show variations based on weather categories.

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
