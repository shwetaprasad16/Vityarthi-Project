# Vityarthi-Project
I have created a project on AQI calculation
🌫️ City AQI Checker

A simple and lightweight Python GUI application built with Tkinter that allows users to check the real-time Air Quality Index (AQI) of major Indian cities.
The app fetches the latest data from the Open-Meteo Air Quality API and displays:

US AQI

PM2.5 concentration

PM10 concentration


📌 Features

✔️ Easy-to-use GUI
✔️ Real-time AQI data
✔️ Dropdown to select popular cities
✔️ Error handling for network/API issues
✔️ Lightweight — no heavy dependencies



🛠️ Technologies Used

Python 3

Tkinter (for GUI)

Requests (for API calls)

Open-Meteo Air Quality API



🚀 How to Run

1️⃣ Install Required Package

Make sure you have requests installed:

pip install requests

2️⃣ Run the Application

Save the script as aqi_checker.py (or any name), then run:

python aqi_checker.py



🧠 How It Works

1. The user selects a city from a dropdown list.


2. The app retrieves latitude and longitude for that city.


3. A request is sent to the Open-Meteo Air Quality API.


4. AQI, PM2.5, and PM10 values are fetched and displayed on the GUI.




🧩 Code Structure

aqi_checker.py
│
├── city_locations      # City names & coordinates
├── fetch_aqi()         # Fetches data from API
├── show_aqi()          # Updates the GUI with API results
└── Tkinter UI Setup    # Buttons, labels, dropdown, layout


🗺️ Supported Cities

(Current list included in the script)

Delhi

Mumbai

Kolkata

Chennai

Bengaluru

Hyderabad

Lucknow


(Add more easily by editing the dictionary!)


⚠️ Notes

Requires an active internet connection.

API returns the first hour of available AQI data.

If the API is unreachable, the app shows an error popup.
