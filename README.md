# Bike-Sharing-Assignment
**Introduction**

The goal of the case study is to build a predictive model (often using regression techniques) to forecast bike rentals, understanding how external factors like weather, time, and holidays influence usage. This helps the business improve fleet management, adjust availability, and target promotions to increase usage, especially during off-peak periods.

It may also involve performing exploratory data analysis (EDA), building machine learning models (such as linear regression or random forests), and validating model performance using metrics like R-squared and mean absolute error (MAE).

**Business Problem:**

BoomBikes, a US-based bike-sharing service, faced revenue losses due to the COVID-19 pandemic. With restrictions easing, the company aims to predict bike demand to optimize operations and boost profitability.
Key Goals:
Identify factors influencing bike demand (weather, season, holidays).
Build a predictive model for accurate demand forecasting.
Use insights to streamline operations, manage inventory, and improve marketing strategies.
Outcome:
The analysis will help BoomBikes make data-driven decisions to meet demand, enhance efficiency, and drive revenue growth post-pandemic.

**Dataset:**

Target Variable:
cnt: Total count of bikes rented (dependent variable).
Independent Variables:
Date and Time:
dteday: Date of observation.
yr: Year (0 = 2011, 1 = 2012).
mnth: Month (1 to 12).
weekday: Day of the week (0 = Sunday).
Season and Holidays:

season: Season (1 = Spring, 2 = Summer, 3 = Fall, 4 = Winter).
holiday: Whether the day is a holiday (1 = Yes, 0 = No).
workingday: Whether the day is a working day (1 = Yes, 0 = No).
Weather Conditions:

weathersit: Weather situation (1 = Clear, 2 = Mist, 3 = Light Snow/Rain, 4 = Heavy Rain).
temp: Normalized temperature (0–1 scale).
atemp: Normalized feeling temperature (0–1 scale).
hum: Normalized humidity (0–1 scale).
windspeed: Normalized wind speed (0–1 scale).
**EDA Data observations & recommendations**






