# 🚀 IoT Predictive Maintenance Dashboard

![Python](https://img.shields.io/badge/Python-3.13+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red.svg)
![Status](https://img.shields.io/badge/Status-Live-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

# IoT Predictive Maintenance Dashboard

A real-time monitoring system for industrial equipment that predicts failures before they happen. Built with Python and Streamlit, it simulates sensor data from motors, pumps, compressors, and other industrial devices.

## What This Project Does

This dashboard monitors 5 industrial devices (motors, pumps, compressors, generators, turbines) and tracks their health in real-time. It shows temperature, vibration, pressure, current, and humidity readings, then calculates health scores and detects anomalies.

## 🌐 Live Demo
👉 You can see the dashboard in action at: (https://iotsystempredictivemaintainencebypriyakhakrode.streamlit.app/)

## Key Features

- **Live sensor monitoring** - temperature, vibration, pressure, current, humidity
- **Health scoring** - calculates device health from 0-100%
- **Anomaly detection** - finds unusual patterns in sensor data
- **Real-time charts** - interactive visualizations of sensor readings
- **Maintenance alerts** - warns when devices need attention

## How It Works

1. **Sensor Simulation** - Creates realistic sensor data with daily patterns and noise
2. **Health Calculation** - Combines sensor readings into a single health score
3. **Anomaly Detection** - Identifies unusual patterns that might indicate problems
4. **Live Updates** - Refreshes data every few seconds to show current status
5. **Visualization** - Charts and metrics show device status at a glance

## Technical Stack

- **Python 3.13+** - Core programming language
- **Streamlit** - Web dashboard framework
- **Pandas & NumPy** - Data processing and calculations
- **Real-time simulation** - Live data updates every 5 seconds

## Dashboard Features

- **5 Industrial Devices** - Motors, pumps, compressors, generators, turbines
- **Real-time Monitoring** - Live sensor data updates
- **Health Scoring** - 0-100% health ratings for each device
- **Anomaly Detection** - Identifies unusual sensor patterns
- **Interactive Charts** - Temperature, vibration, pressure, current trends

## Getting Started

1️⃣. Clone the repository
```bash
git clone (https://github.com/priyakhakrode02/Predictive-Maintenance-System-for-Industrial-IoT-using-Machine-Learning)
```

2️⃣. Install dependencies
```bash
pip install -r requirements.txt
```

3️⃣. Run the dashboard
```bash
streamlit run app.py
```

4️⃣. Open your browser to `http://localhost:8501`

## Project Structure

```
iot-predictive-maintenance/
├── app.py                 # Main dashboard application
├── requirements.txt       # Python dependencies
├── README.md             # This file
├── src/                  # Source code modules
│   ├── data_generator.py # Sensor data simulation
│   ├── anomaly_detector.py # ML models
│   ├── data_processor.py # Data processing
│   ├── streamlit_app.py  # Streamlit components
│   └── utils.py          # Helper functions
├── notebooks/            # Data analysis notebooks
│   └── data_exploration.ipynb
└── config/              # Configuration files
    └── config.yaml
```

## 🌐 Live Demo

You can see the dashboard in action at: https://iot-predictive-maintenance-system.streamlit.app/

## Features in Detail

- **🚀Real-time Data** - Simulates sensor readings with realistic patterns
- **📳Health Monitoring** - Calculates device health from sensor data
- **🚨Anomaly Detection** - Finds unusual patterns that need attention
- **📈Interactive Charts** - Live charts showing sensor trends
- **📊Device Status** - Shows current status of all 5 devices
- **🔔Maintenance Alerts** - Recommends when devices need service

It continuously tracks:

- 🌡 Temperature  
- 📳 Vibration  
- 🔵 Pressure  
- 🔌 Current  
- 💨 Humidity  


## Deployment

This dashboard is designed to run on Streamlit Cloud. The main file is `app.py` with minimal dependencies in `requirements.txt`.
