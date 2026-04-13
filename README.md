# 🚗 Shell Eco-Marathon 2026 – Data & Telemetry AI System

## 🏆 Achievement

🥈 **2nd Place Winner** in *Data & Telemetry* category at **Shell Eco-Marathon 2026 (Qatar)**
🌍 Competed against 70+ international teams
🇪🇬 First Egyptian & Arab team to win in a main category

---

## 📌 Overview

This project presents an intelligent system designed to optimize vehicle energy consumption during a race track while meeting strict time constraints.

The solution integrates:

* Physics-based simulation (core decision system)
* AI-based prediction (decision support system)

The goal is to achieve **maximum efficiency with minimum energy usage**.

---

## 📊 Data Description

Available raw data included:

* Latitude
* Longitude
* Altitude
* Distance

Since raw GPS data is not directly usable for modeling, extensive feature engineering was performed.

---

## ⚙️ Feature Engineering

Constructed meaningful features from raw data, including:

* Lap position normalization
* Slope calculation
* Conversion from GPS to Cartesian coordinates (X, Y)
* Curve detection
* Speed limits estimation for each curve

---

## 🧠 Physics-Based Simulation

A detailed simulation model was built to replicate real vehicle behavior on the track, considering:

* Vehicle dynamics
* Road characteristics
* Energy consumption

### 🔧 Optimization Strategy:

* Applied **Pulse & Glide technique**
* Tuned optimal speed thresholds (**v_low, v_high**)

### 📈 Results:

* Lap Time: **9.14 minutes**
* Total Race Time: **34.8 minutes**
* Energy per Lap: **10.45 Wh**
* Total Energy Consumption: **39.8 Wh (~7.6% of battery capacity)**

---

## 🤖 AI Model (LSTM)

A time-dependent deep learning model was developed to:

* Predict power profile across the track
* Assist in optimal decision-making

### Approach:

* Segmented the track into multiple sections
* Trained LSTM model on engineered features and real vehicle data
* Achieved predictions closely matching simulation results

---

## ⚡ Key Insight

The system was designed such that:

* **Physics-based simulation acts as the primary decision-maker**
* **AI acts as a guidance layer**

This hybrid approach reflects real-world intelligent systems used in autonomous driving technologies.

---

## 🚀 Deployment

The model was successfully deployed on the vehicle in collaboration with the Embedded Systems team, enabling real-time decision support.

---

## 🛠 Technologies Used

* Python
* NumPy, Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

---

## 👩‍💻 Author

**Mai Kamal**
AI Engineer & Data Scientist
# Shell-Eco-Marathon-Data-Telemetry-project
