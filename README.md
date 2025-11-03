# 🚦 Dynamic Traffic Optimization



## 📘 Project Overview

**Dynamic Traffic Optimization** is an intelligent control system that enhances urban mobility using **Cloud Computing**, **Big Data Analytics**, and **Machine Learning**. It dynamically adjusts traffic signals based on data to predict and reduce congestion efficiently.

---

## 🧠 Key Objectives

- Minimize **traffic congestion** using predictive analytics.  
- Apply **Random Forest** models for congestion forecasting.  
- Utilize **MongoDB Atlas** and **Apache Spark** for scalable data management.  
- Provide a **Streamlit dashboard** for simulation and visualization.  
- Improve **travel time**, **fuel efficiency**, and **urban safety**.

---

## 🏗️ System Architecture

```
 ┌──────────────────────────┐
 │ Data Sources             │
 │ (Sensors, GPS, Social)   │
 └────────────┬─────────────┘
              │
              ▼
 ┌──────────────────────────┐
 │ Cloud Integration Layer  │
 │ (MongoDB Atlas)          │
 └────────────┬─────────────┘
              │
              ▼
 ┌──────────────────────────┐
 │ Machine Learning Model   │
 │ (Random Forest)          │
 └────────────┬─────────────┘
              │
              ▼
 ┌──────────────────────────┐
 │ Streamlit Visualization  │
 │ (Traffic Dashboard)      │
 └──────────────────────────┘
```

---

## ⚙️ Methodology

1. **Data Collection:** Acquire traffic data from IoT sensors, GPS, and weather APIs.  
2. **Cloud Integration:** Store and manage large datasets using MongoDB Atlas.  
3. **Data Processing:** Use **Apache Spark** for distributed cleaning, transformation, and aggregation.  
4. **Prediction:** Employ a **RandomForest** model to forecast congestion and traffic flow.  
5. **Visualization:** Present insights and signal recommendations on a **Streamlit dashboard**.

---

## 🧩 Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.x |
| **Frontend** | Streamlit |
| **Machine Learning** | Scikit-learn (RandomForest) |
| **Data Analytics** | Pandas, NumPy, Matplotlib |
| **Database** | MongoDB Atlas |
| **Big Data** | Apache Spark |
| **Version Control** | Git & GitHub |

---

## ⚙️ Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/Vineethkolli/Traffic_Optimiazation_Minor_Project
cd Traffic_Optimiazation_Minor_Project
```

### Install Dependencies
```bash
pip install streamlit pandas numpy matplotlib scikit-learn pymongo joblib
```

### Run the Streamlit Dashboard
```bash
streamlit run app.py
```

---

## 📊 Features

✅ **Simulate Real-Time Traffic Data** – Adjustable parameters (weather, time, speed, vehicle count).  
✅ **MongoDB Integration** – Stores and retrieves traffic records dynamically.  
✅ **Traffic Prediction Dashboard** – Displays live traffic data and visual analytics.  
✅ **Machine Learning Integration** – Predicts congestion levels using RandomForest.  
✅ **Dynamic Traffic Light System** – Adjusts signal color (Green/Red) based on traffic density and speed.  

---

## 📈 Results (from Simulation)

| Metric | Result |
|---------|---------|
| **Prediction Accuracy** | 92% |
| **Average Travel Time Reduction** | 18% |
| **Congestion Reduction** | 25% |
| **System Response Time** | < 2 seconds |

---

## 🔮 Future Enhancements

- Integrate **deep learning models (LSTM/CNN)**.  
- Connect **IoT** devices for live data streaming.  
- Implement **real-time map visualization (Google Maps API)**.  

---

## 🏆 Publication

**Paper Title:**  
*Dynamic Traffic Optimization through Cloud-Enabled Big Data Analytics and Machine Learning for Enhanced Urban Mobility*

**Conference:**  
IEEE 5th International Conference on Data Intelligence and Cognitive Informatics (ICDICI-2024)

**DOI:** [10.1109/ICDICI62993.2024.10810771](https://doi.org/10.1109/ICDICI62993.2024.10810771)

---

## 👨‍💻 Contributors

| Name | Role |
|------|------|
| **Kolli Vineeth** | Project Lead, ML Developer, Streamlit Integration |
| **Kothoju Naresh** | Backend Developer, MongoDB Integration |
| **G. Gari Prabhash Reddy** | Data Analyst, Visualization & Report Writer |
| **Dr. R. Naresh** | Research Guide |

