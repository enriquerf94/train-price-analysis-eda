# 🚄 Renfe Price Analysis - EDA

This project explores train ticket prices in Spain through an Exploratory Data Analysis (EDA) approach. The goal is to understand price patterns, relationships between variables and prepare the dataset for potential predictive modeling.

---

## 📊 Project Overview

The analysis includes:

- Data cleaning and preprocessing
- Handling missing values and duplicates
- Feature engineering (time-based variables, trip duration)
- Exploratory visualizations
- Correlation analysis
- One-hot encoding for categorical variables

---

## 🧠 Key Insights

- Trip duration shows a slight negative correlation with price
- Geographic location has a weak influence on pricing
- No strong linear relationships were found between numerical variables and price
- Price likely depends on additional external factors (demand, distance, train type)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly Express
- Jupyter Notebook

---

## 📁 Dataset

The dataset contains information about train trips, including:

- Origin and destination cities
- Train type and ticket class
- Departure time and date
- Price

Additional dataset:
- City coordinates for geospatial visualization

---

## 📈 Visualizations

The project includes:

- Histograms of trip duration
- Scatter plot (price vs travel time)
- Boxplot (price vs day of the week)
- Average price per day of the week
- Map visualization of average prices by destination

---

## 🔧 Feature Engineering

New features created:

- Trip duration (in minutes)
- Day of the week
- Month
- Departure hour

Categorical variables were transformed using one-hot encoding for future modeling purposes.

---

## 🚀 Next Steps

Possible improvements:

- Include distance between cities
- Incorporate demand-related features
- Build predictive models (regression / ML)
- Apply cyclical encoding for time-based variables

---

## 📌 Author

Enrique Rodríguez

---

## 💡 Notes

This project is part of a Data Science learning process and focuses on understanding data rather than building production-ready models.
