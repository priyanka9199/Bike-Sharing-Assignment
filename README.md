# Bike-Sharing-Assignment
Introduction

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

There is an increase in the number of bike users from 2018 (0) to 2019 (1).

More users are observed during holidays (0) compared to non-holidays (1).

The difference in bike users between working days (1) and non-working days (0) is minimal.

There were six categorical variables in the dataset, and we used boxplots to examine their impact on the target variable 'cnt' (total bike bookings). Here are the key takeaways:

Season:

Around 32% of bike bookings occurred in season 3 (fall), with a median of over 5000 bookings across two years. Season 2 (summer) and season 4 (winter) followed with 27% and 25% of total bookings, respectively. This suggests that the season is a strong predictor for bike bookings.

Month (mnth):

Around 10% of bookings happened in the months of May, June, July, August, and September, with a median of over 4000 bookings per month. This indicates that the month has a clear trend in bookings and could also be a good predictor.

Weather Situation (weathersit):

67% of bookings occurred in weather situation 1, with a median close to 5000 bookings. Weather situation 2 accounted for 30% of bookings. This shows that weather conditions influence bike bookings and can be a useful predictor.

Holiday:

97.6% of bookings happened when it was not a holiday. This highly imbalanced distribution means holiday is not a useful predictor for bike bookings. Weekday:

The distribution of bookings across weekdays was similar, with each day having around 13.5%-14.8% of total bookings, and medians between 4000-5000 bookings. This suggests weekday may have minimal or no impact on bike bookings. The model can help decide whether it should be included.

Working Day:

About 69% of bookings occurred on working days, with a median close to 5000 bookings.

This indicates that working day can be an important predictor for bike bookings.

**Conclusion:**

Season, month, weathersit, and working day are strong predictors of bike bookings.

Holiday is not a useful predictor due to its bias.

Weekday may or may not influence bookings, and the model will decide its importance.

**Technologies Used**

eaborn 0.11.1

jupyter 1.0.0

numpy 1.20.1

anaconda 2021.05

python 3.8.8

matplotlib 3.3.4

Microsoft excel

Scikit-learn 

Statsmodels

**Acknowledgements**

Thanks upgrad team

**Contacts**

Created by priyanka kumari - feel free to contact me!




