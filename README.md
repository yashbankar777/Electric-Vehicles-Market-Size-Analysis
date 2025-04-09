🔋 Electric Vehicle (EV) Population Data Analysis

This repository provides a comprehensive exploratory data analysis (EDA) and trend forecasting of Electric Vehicle registrations using real-world EV data.

📊 Project Overview

This project analyzes trends in electric vehicle adoption, regional preferences, popular manufacturers and models, and electric range statistics. It also forecasts future adoption using exponential curve fitting.

📁 Dataset
The dataset used is:

Electric_Vehicle_Population_Data.csv
Source: [Washington State Department of Licensing or other similar public domain]

It contains key information including:

Vehicle Make & Model

Model Year

Electric Range

County & City

EV Type (Battery Electric, Plug-in Hybrid, etc.)

🛠️ Libraries Used
pandas

numpy

matplotlib

seaborn

scipy.optimize

📈 Key Analyses & Visualizations
✅ Data Preprocessing
Loaded dataset using pandas

Identified and removed null entries to ensure data quality

📉 EV Adoption Over Time
Bar chart showing yearly trend of EV registrations

🌍 Geographic Insights
Top 3 counties with highest registrations

Top cities within those counties

Bar plots visualizing city-wise distribution

🚗 Vehicle Type & Make
Distribution of EV types (Battery Electric, Plug-in Hybrid, etc.)

Top 10 popular EV manufacturers

Top models within top 3 manufacturers

⚡ Electric Range Analysis
Histogram showing range distribution

Line plot showing average electric range by year

Top 10 EV models by electric range within popular manufacturers

📈 Growth Forecasting
Fitted exponential curve to historical registration data

Forecasted EV registrations from 2024 to 2029

Visualized actual vs forecasted adoption trends

