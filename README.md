# Motor-Vehicle-Collisions-Crashes

Navigating Manhattan: Traffic Analysis During Holidays and Major Events  

📌 Overview  
This project explores how holidays and major events affect traffic collisions in Manhattan.  
By analyzing trends from NYC Open Data, we aim to identify patterns in crash severity, frequency, and contributing factors, ultimately providing insights for:  
- Commuters and drivers  
- Public transportation planning  
- Businesses affected by seasonal traffic changes  
- City agencies seeking improved traffic regulation strategies  


🎯 Objectives  
- Compare collision rates during holidays/events vs. regular days* 
- Use statistical tests (e.g., t-tests) to evaluate differences  
- Apply regression models to quantify the effects of specific events  
- Visualize patterns in traffic and collisions over time  

📊 Data Sources  
1. Motor Vehicle Collisions – Crashes (NYC Open Data)
  - Variables: crash date/time, borough, injuries/fatalities, vehicle type, contributing factors  
2. Automated Traffic Volume Counts (NYC Open Data)
   - Automated traffic recorder counts at bridge crossings and roadways  
3. External datasets for holiday calendars and major NYC events

🛠️ Methodology  
1. Data Cleaning & Preparation
   - Select relevant variables (date, borough, crash severity, vehicle type, etc.)  
   - Create derived features (e.g., holiday vs. non-holiday, weekday/weekend, event tags)  

2. Exploratory Data Analysis (EDA)
   - Plot time-series of crash counts  
   - Compare severity across holidays and events  

3. Statistical Analysis  
   - Conduct Welch’s t-tests to compare crash metrics (holidays vs. non-holidays)  
   - Run regression models (Poisson/OLS) controlling for weather, time of day, etc.  
