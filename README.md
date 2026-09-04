# HackTitans---Suvan-Rai

# AI-Powered Personalized Weather & AQI Health Advisory
EnviroGuard AI is an intelligent environmental health advisory system that combines real-time weather and Air Quality Index (AQI) data with user-specific information to provide personalized environmental risk insights.

Unlike generic weather and AQI applications that provide the same warning to everyone, EnviroGuard AI considers factors such as age group, health condition, and occupation/activity level to generate recommendations tailored to the individual.

# 🎯 Problem Statement

Generic weather and AQI alerts use the same thresholds for everyone, even though environmental conditions can affect people differently.

For example, an outdoor worker and an indoor student may experience the same AQI but have very different levels of exposure.

EnviroGuard AI aims to bridge this gap by transforming environmental data into personalized, actionable guidance.

# 💡 Our Solution

EnviroGuard AI follows a simple pipeline:

User Profile → Live Weather & AQI → Risk Analysis → AI Personalization → Actionable Advisory

The system provides:

🌫️ Real-time AQI information

🌡️ Current weather conditions

👤 Personalized user profiles

🧠 AI-generated environmental advisories

⚠️ Personalized risk classification

📈 Environmental trends and history

🔮 What-If environmental scenario simulation

✨ Key Features

# 🌤️ Real-Time Environmental Dashboard

Displays important environmental parameters such as:

AQI

Temperature

Humidity

Wind conditions

Weather information


# 👤 Personalized Risk Assessment

The system considers user information such as:

Age group

Health condition

Occupation/activity level

to provide a more relevant risk assessment.


# 🤖 AI-Powered Advisory

An AI layer converts environmental conditions and user information into simple, understandable recommendations.

# 📈 Trend Analysis

Users can view historical environmental conditions and identify whether air quality is improving or worsening.

# 🔮 What-If Simulator

Users can simulate changes in environmental conditions and see how the personalized risk level changes.

For example:

"What happens to my environmental risk if AQI increases from 150 to 300?"

This helps users understand potential environmental scenarios instead of simply receiving a static warning.

# 🛠️ Technology Stack

Frontend

Streamlit

Backend

Python

APIs & Data

Open-Meteo for weather data

AQI data source/API

AI

Free-tier LLM API

Visualization

Plotly / Streamlit Charts

Database

SQLite


# 🏗️ System Architecture

 User
 
 ↓

Profile & Location

 ↓

Live Weather + AQI Data

 ↓

Data Processing

 ↓

Personalized Risk Engine

 ↓

AI-Based Analysis

 ↓

Personalized Advisory

 ↓

Risk Level + Recommendations

 ↓

Dashboard

 ↓

7-Day Trends + What-If Simulation

 ↓

User


# 🚀 Future Scope

Possible future improvements include:

📍 Automatic location detection

🔔 Smart environmental alerts

🗺️ City-wise environmental risk maps

📱 Mobile application

🎙️ Voice-based interaction

📊 Long-term personal exposure analytics

🧠 Improved predictive environmental risk models
