c

A comprehensive analysis of factory sensor data for predictive maintenance and failure prediction.

📋 Overview

This project analyzes factory sensor data from 500,000 industrial machines to predict machine failures within 7 days. The analysis includes data exploration, visualization, statistical analysis, and machine learning models for failure prediction.

📁 Files

- `data.ipynb` - Main Jupyter notebook with complete analysis
- `factory_sensor_simulator_2040.csv` - Dataset containing 500,000 machine records: https://www.kaggle.com/datasets/canozensoy/industrial-iot-dataset-synthetic
- 

 🔍 Dataset Description

The dataset contains sensor readings and operational metrics for various industrial machines:

 Machine Types (33 types)
- AGV, Shuttle System, Crane, Labeler, CNC Lathe, Industrial Chiller
- CMM, Pump, Vacuum Packer, Injection Molder, Automated Screwdriver
- Mixer, Valve Controller, Vision System, Laser Cutter, Compressor
- And 18 more types...

Features
- Machine Info:Machine_ID, Machine_Type, Installation_Year
- Sensor Data: Temperature, Vibration, Sound, Oil Level, Coolant Level, Power Consumption
- Maintenance: Last_Maintenance_Days_Ago, Maintenance_History_Count, Failure_History_Count
- AI Features: AI_Supervision, Error_Codes_Last_30_Days, AI_Override_Events
- Predictive: Remaining_Useful_Life_days, Failure_Within_7_Days (target)

Statistics
- Total Records: 500,000 machines
- Failure Rate: 6.01% (30,032 machines will fail within 7 days)
- Missing Data: Some specialty sensors (Laser_Intensity, Hydraulic_Pressure_bar, etc.) have high missingness rates

Project Goals

1. Exploratory Data Analysis (EDA)
   - Distribution of machine types
   - Failure rate analysis by machine type
   - Sensor reading comparisons between failed and healthy machines

2. Predictive Modeling
   - Build machine learning models to predict failures
   - Identify key indicators of impending failure
   - Evaluate model performance

3. Key Insights
   - Which sensor readings are most indicative of failure
   - Impact of AI supervision on failure rates
   - Maintenance schedule optimization opportunities

