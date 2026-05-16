# README.md  
## AI Chatbot for Increasing Building Sustainability Using Data Science

### Project Overview
This project presents an AI-powered chatbot integrated with Data Science and Machine Learning techniques to improve building sustainability and energy efficiency. The system analyses occupancy, environmental, and weather-related data to provide intelligent insights, occupancy forecasting, and sustainability recommendations for smart building management.

The chatbot enables users to interact with the system using natural language queries and receive real-time analytical responses regarding building occupancy, environmental conditions, CO₂ levels, room utilisation, and sustainability metrics.

---

# Key Features

- AI-powered conversational chatbot
- Occupancy prediction using Machine Learning
- Smart building sustainability analytics
- Real-time environmental monitoring
- Interactive dashboard visualisation
- CO₂ and temperature analysis
- Underutilised room detection
- Energy optimisation support
- Natural Language Processing (NLP) interaction

---

# Technologies Used

## Programming Language
- Python

## Machine Learning & Data Science Libraries
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Dashboard & UI
- Streamlit
- Plotly


## Development Environment
- Google Colab
- Jupyter Notebook

---

# System Architecture

The system consists of multiple integrated layers:

1. Data Collection Layer  
   - Occupancy data  
   - Environmental sensor data  
   - Weather data  

2. Data Processing Layer  
   - Data cleaning  
   - Feature engineering  
   - Missing value handling  

3. Machine Learning Layer  
   - Random Forest Regression  
   - XGBoost Regression  
   - Occupancy forecasting  

4. Dashboard Layer  
   - KPI visualisation  
   - Occupancy heatmaps  
   - Sustainability analytics  

5. Chatbot Layer  
   - Intent recognition  
   - Conversational AI responses  
   - Real-time analytical support  

---

# Machine Learning Models

The project uses the following regression models:

| Model | Purpose |
|---|---|
| Linear Regression | Baseline prediction |
| Random Forest | Occupancy forecasting |
| XGBoost | High-accuracy prediction |

### Model Performance
- **R² Score:** 0.995
- **Low RMSE and MAE**
- High prediction accuracy for occupancy analytics

---

# Chatbot Functionalities

The chatbot supports intelligent queries such as:

- Highest occupied room
- Current CO₂ levels
- Temperature analysis
- Underutilised rooms
- Occupancy summaries
- Humidity monitoring
- Sustainability overview
- Date-range analytics

### Example Questions
```plaintext
Which room has the highest occupancy?
Show rooms with high CO₂ levels.
What is the hottest room right now?
Give sustainability summary.
```

---

# Dataset Information

The dataset includes:
- Occupancy records
- Temperature
- Humidity
- CO₂ levels
- Weather information
- Room hierarchy data
- Time-series environmental metrics

---

# Project Workflow

```plaintext
Data Collection
       ↓
Data Cleaning & Preprocessing
       ↓
Feature Engineering
       ↓
Machine Learning Training
       ↓
Model Evaluation
       ↓
Dashboard Integration
       ↓
AI Chatbot Integration
       ↓
Sustainability Analytics
```

---

# Installation Guide

## Clone Repository
```bash
git clone <repository-link>
cd smart-building-chatbot
```

## Install Dependencies
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn streamlit plotly groq
```

---

# Running the Project

## Run Jupyter Notebook
```bash
jupyter notebook
```

## Run Streamlit Dashboard
```bash
streamlit run app.py
```

---

# Folder Structure

```plaintext
project/
│
├── CHATBOT.ipynb
└── README.md
```

---

# Dashboard Features

- Occupancy heatmaps
- Top utilised rooms
- Environmental monitoring
- Sustainability KPIs
- Predictive occupancy trends
- Interactive visual analytics

---

# Future Enhancements

- Real-time IoT sensor integration
- Deep Learning models (LSTM/GRU)
- Voice-enabled chatbot
- Automated HVAC optimisation
- Cloud deployment
- Renewable energy optimisation
- Smart city integration

---

# Applications

- Smart Buildings
- Sustainable Infrastructure
- Energy Management Systems
- Smart Campuses
- Intelligent Facility Management
- Green Building Analytics

---

# Conclusion

This project demonstrates how Artificial Intelligence, Machine Learning, and Data Science can improve building sustainability through predictive analytics and intelligent automation. The chatbot-based interface enhances accessibility to sustainability insights and supports efficient building management decisions using real-time analytical interaction.

---
