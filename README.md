# Fire_Classification_AI/ML_Internship_Edunet
- [📈Internship Weekly Progress Report Check](#internship-progress-report)
<div align="right"><h4><b>Mentor:</b> Raghunandan M S</h4>
<i>Data Scientist/Analyst & Trainer</i></div>

>start Date: 15th July 2025
>>End Date: ...

## Classification of Fire Types in India Using MODIS Satellite Data (2021–2023)

India witnesses various types of fire incidents annually, including forest fires, agricultural burning, volcanic activity, and other thermal anomalies. Accurate identification of fire sources is crucial for timely disaster response, environmental monitoring, and resource management. The MODIS sensors aboard NASA’s Terra and Aqua satellites provide reliable, near real-time thermal anomaly data globally, including for India.

While the MODIS dataset includes rich geospatial and thermal parameters, the challenge lies in correctly classifying the type of fire event — whether it stems from vegetation, volcanoes, static land sources, or offshore sources — using satellite-captured features.

### Objective:
To develop a machine learning classification model that can accurately predict the type of fire using MODIS fire detection data for India from 2021 to 2023

### 🔥 MODIS Dataset Summary (India: 2021–2023)
#### 📌 About MODIS:
The Moderate Resolution Imaging Spectroradiometer (MODIS) is a key NASA sensor aboard the Terra (launched 1999) and Aqua (launched 2002) satellites. It captures Earth observation data at a spatial resolution of 1 km, suitable for global fire monitoring and environmental studies.

MODIS data used in this project is sourced from NASA’s FIRMS (Fire Information for Resource Management System) and focuses on thermal anomalies and active fire detection.

## 🛰️ Satellite Characteristics:
Terra satellite (EOS AM) captures morning overpasses.

Aqua satellite (EOS PM) captures afternoon overpasses.

MODIS provides 2–4 observations per day, especially in mid-latitudes like India.

## 🔍 Fire Detection Mechanism:
*MODIS uses contextual algorithms to detect thermal anomalies.*

*It evaluates each pixel using mid-infrared channels (Bands 21/22 for  fire detection and 31 for surface temperature).*

*The pixel is marked as one of: missing, cloud, water, non-fire, fire, or unknown.*




### ⚠️ Note on Accuracy:
MODIS NRT (Near Real-Time) data may have slightly lower geolocation accuracy, particularly from Aqua satellite due to orbit estimation delays. Errors can occasionally reach several kilometers.



### ✅ Use Cases for MODIS Fire Data:
Real-time wildfire alerts

Agricultural burn detection

Forest fire management

Hotspot pattern analysis in ecological studies



### 📚 Reference Links:

[🔗 NASA FIRMS Documentation](https://www.earthdata.nasa.gov/data/tools/firms)

[🔗 Global Fire Data Access Porta](https://firms.modaps.eosdis.nasa.gov/download/)

### 🛠️ Tools & Environment

- **Language**: Python 3.12.10  
- **IDE**: VS Code with Jupyter Notebook  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

---

# Internship Progress Report

## 📅 Week 1 – Completed ✅

**Focus:** Data Collection, Cleaning, and EDA

- Loaded MODIS fire datasets (2021–2023)  
- Merged and cleaned data  
- Checked for missing/duplicate values  
- Explored categorical features  
- Visualized fire types and confidence distribution

---


## 📅 Week 2 – Completed ✅  
**Focus:** Feature Engineering and Preprocessing

- Created temporal features (month, day of week, hour)  
- Visualized trends and correlations  
- Detected and removed outliers (IQR method)  
- Applied one-hot encoding to categorical features  
- Scaled numerical features using StandardScaler  
- Balanced classes using SMOTE  

---

## 📌 Upcoming Progress

- **Week 3** – *(Coming Soon...)*

---

