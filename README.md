# Full_Water_Irrigation_Project
The stack includes a frontend, a FastAPI backend, a machine learning model, the Open-Meteo weather API, and a Dockerized PostgreSQL database.
We built an automated Smart Irrigation System that dynamic controls plant watering using real-time IoT data and predictive analytics.
How it works:
Hardware & IoT: Used an ESP32 microcontroller with DHT11 temperature,  humidity and soil moisture sensors to track real-time conditions.
Backend & ML Integration: The backend evaluates live soil moisture data, temperature and humidity alongside predictions from a Machine Learning model and external Weather API data.
Smart Automation: Instead of simple thresholding, the system factors in current hardware inputs, forecast weather using openmetro and ml model to decide whether to activate the pump—saving water and optimizing crop health.
