# ☁️ Energy Demand and Weather Analysis

**📌 Description:**
This project investigates the relationship between electricity demand and weather patterns, particularly temperature fluctuations, using data from the Australian Energy Market Operator and the Bureau of Meteorology.

**🛠 Features:**

* Data-Driven Analysis: Leveraged 20 years of energy consumption and weather data (2000–2019).
* Advanced Modeling: Explored machine learning models, with random forests proving most effective.
* Seasonal Insights: Found that summer demand was easier to predict, while winter presented challenges.
* Explainability: Identified temperature as the most influential factor, with a strong correlation to energy demand.

**📂 Dataset/Resources:**

* Energy Demand Data: Australian Energy Market Operator (AEMO)
* Weather Data: Bureau of Meteorology (BOM) Automatic Weather Stations
* Additional Variables: Humidity, wind speed, precipitation, and pressure

  
**💻 Tech Stack: **

* Python, Pandas, Scikit-learn, Random Forests


📊 Results & Insights:

* Strong Parabolic Relationship: Energy demand is highest in extreme temperatures (air conditioning/heating).
* City & Seasonal Variability: Models needed separate tuning for each season and city due to climate differences.
* Predictability: Summer demand was easiest to model, while autumn and spring showed less distinct trends.
* Feature Importance: Temperature had the highest influence on demand, often scoring above 0.8 in feature importance.
