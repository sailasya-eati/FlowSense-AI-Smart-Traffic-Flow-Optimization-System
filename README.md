
# 🚦 FlowSense AI – Smart Traffic Flow Optimization System

This repository contains a machine learning project that predicts traffic flow and analyzes congestion patterns using synthetic traffic data.

## 📁 Files Included
- **traffic_dataset.csv** – Synthetic dataset with traffic statistics
- **main.py** – Python script for training and prediction
- **README.md** – Project documentation

## 📊 Dataset Columns
- **timestamp** – Time of measurement  
- **lane_id** – Lane number (1–4)  
- **vehicle_count** – Number of vehicles detected  
- **avg_speed_kmph** – Average speed  
- **weather** – Clear/Rain/Fog/Cloudy  
- **is_peak_hour** – 1 = peak traffic, 0 = non-peak  

## 🧠 Model Used
- Random Forest Regressor  
- Predicts vehicle count based on traffic conditions  

## ▶ How to Run
```bash
pip install pandas scikit-learn
python main.py
```

