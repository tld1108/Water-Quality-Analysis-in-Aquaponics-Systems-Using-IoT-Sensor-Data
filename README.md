# Water-Quality-Analysis-in-Aquaponics-Systems-Using-IoT-Sensor-Data
This project analyzes water quality using IoT sensor data to understand environmental conditions within an aquaponics system.

---
Aquaponics is a sustainable farming system that combines aquaculture (fish farming) and hydroponics (soil-less plant cultivation). Maintaining water quality is crucial to ensure a balanced ecosystem for both fish and plants.

---

# Objectives

1. Analyze relationships between water quality parameters
2. Identify trends and patterns over time
3. Detect potential abnormal conditions
4. Provide data-driven recommendations

---

# Dataset

The dataset is sourced from Kaggle (Aquaponics Dataset) and contains real-world sensor data collected from an aquaponics system.

Parameters:
1. pH (acidity level)
2. DO2 (Dissolved Oxygen)
3. Ammonium
4. Salinity
5. Nitrite
6. Timestamp (readTime)

---

# Data Preprocessing

The following steps were performed:

1. Merged multiple JSON files into a single dataset
2. Extracted sensor type from file names
3. Consolidated sensor values into a unified column (value)
4. Converted data types from string to numeric
6. Reshaped the dataset using a pivot table
7. Converted timestamps into datetime format
8. Handled missing values using forward fill

--- 
# Exploratory Data Analysis (EDA)
1. Correlation Analysis
   Used to examine relationships between water quality parameters.
3. Time Series Analysis
   Visualized how sensor values change over time.
5. Statistical Summary
   Descriptive statistics were used to understand data distribution.

---
# Key Insights

1. DO2 levels are relatively stable, indicating sufficient oxygen levels
2. Increasing ammonium levels may indicate declining water quality
3. pH fluctuations suggest the need for more consistent monitoring
4. Some parameters show relationships that can be useful for early issue detection

---
# Recommendations

1. Regularly monitor pH and ammonium levels
2. Maintain stable dissolved oxygen levels (DO2
3. Implement alert systems for extreme changes
4. Develop a real-time monitoring dashboard

---
# Tools & Technologies
1. Python (Pandas, Matplotlib, Seaborn)
2. Google Colab
3. GitHub

---
# Project Structure

```text
aquaponic-water-analysis/
│
├── data/
├── notebook.ipynb
├── README.md
```
--- 

# Future Improvements
1. Implement anomaly detection techniques
2. Apply machine learning for water quality prediction
3. Build an interactive dashboard (Tableau / Power BI)
