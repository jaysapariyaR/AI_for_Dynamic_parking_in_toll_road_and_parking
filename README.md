# 🚗 AI for Dynamic Pricing in Toll Roads and Parking 

## 🧠 Problem Statement

Traditional fixed pricing for toll roads and parking facilities leads to inefficiencies:
- Overcrowded zones during peak hours
- Underutilized spaces during off-peak
- Lost revenue opportunities
- No incentive for users to travel during low-demand hours

This project presents an **AI-powered dynamic pricing system** that adjusts toll and parking rates in real-time based on various factors like:
- Traffic conditions
- Time of day
- Occupancy rate
- Weather
- Holidays and user behavior

By implementing AI-based dynamic pricing, this system aims to:
- Reduce congestion during peak hours
- Maximize facility usage
- Simulate user behavior to evaluate acceptance
- Provide flexible control to authorities via a dashboard or API

---

## 🎯 Project Objectives

✅ Build a machine learning model to:
- Determine optimal toll/parking prices using historical and real-time data  
- Predict high-demand periods and adjust pricing dynamically  
- Simulate user response to pricing changes  
- Provide a visual dashboard for real-time decision-making  
- Offer API endpoints for easy integration with real toll/parking systems  

---

## 🛠️ Project Features

- ✅ Historical Usage dataset simulating real-world demand scenarios  
- ✅ Preprocessing and label encoding for categorical features  
- ✅ Machine Learning model (RandomForestRegressor) to predict price  
- ✅ Dynamic pricing logic based on demand signals  
- ✅ User behavior simulation  
- ✅ Interactive dashboard built with **Streamlit**  
- ✅ REST API using **Flask** for system-level integration



## ⚙️ Setup Instructions

### 1. Clone the repository and enter the project folder:

```bash
git clone https://github.com/your-username/ai-dynamic-pricing.git
cd ai-dynamic-pricing


2. Install all required packages:

'''
bash

pip install -r requirements.txt

'''

🚀 Usage Guide

✅ Step 1: Train the model (and generate model.pkl and label_encoders.pkl)

'''
bash

python train_model.py
'''

In This Model Include:
Loading dataset
Preprocesses and encodes data
Trains a RandomForestRegressor
Saves the model and label encoders


✅ Step 2: Run the Dashboard (Streamlit)

'''
bash

streamlit run app.py
'''

This opens a visual UI where traffic managers can:

Select real-time traffic/occupancy/weather inputs

View the suggested dynamic price

Simulate how users may respond to that price



<img width="1000" height="431" alt="UI Dashboards1" src="https://github.com/user-attachments/assets/19bfcb83-3867-438a-a3c6-8809a24398ef" />
<img width="1027" height="778" alt="UI Dashboards" src="https://github.com/user-attachments/assets/154ac6d0-4a7f-40ab-9136-707c5f893f83" />










