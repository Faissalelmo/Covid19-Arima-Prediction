# 🧠 Predicting COVID-19 Cases in Morocco with Machine Learning

Real-time data has become a dominant aspect for understanding past, present, and future situations. Machine Learning (ML) is one such subject that uses a variety of algorithms to understand the correlation between the given data, visualize the current scenario, and predict the future forecast which is the most crucial part. The entire world is currently undergoing a devastating situation due to the outbreak of novel coronavirus known as COVID-19. The COVID-19 at present has proved that it is a potential threat to human life. To contribute to control the spread and rising number of active cases in India, this study demonstrates the future forecasting of the total number of active cases in India in the upcoming 15 days. The future forecast is predicted using the ARIMA Model (Auto-regressive Integrated Moving Average) with the combination of Facebook Prophet which gives us the highest accuracy. The real-time data collection takes place from various resources after which the data pre-processing and data wrangling takes place. The data set is then split into the training set and testing set. Finally, the model is trained and tested for accuracy. With the completion of testing and training, the model is ready to predict future forecasts. The model also makes note of the predicted and actual values which helps it achieve higher accuracy in the future.
This repository presents a **Personalized Machine Learning Project** aimed at analyzing and predicting the spread of **COVID-19 cases in Morocco** using real-world data. The project follows a full data science pipeline — from data acquisition and exploration to modeling and evaluation.

---

## 📌 Project Goal

To apply machine learning techniques to predict future confirmed COVID-19 cases in Morocco, based on historical trends. This project supports informed decision-making and public health planning.

---

## 📊 Dataset Overview

The dataset contains daily COVID-19 statistics from Morocco and includes the following key features:

- `Date` – Reporting date  
- `Confirmed` – Total confirmed cases  
- `Deaths` – Total deaths  
- `Recovered` – Total recoveries  
- Regional columns (e.g., `Casablanca-Settat`, `Fès-Meknès`, etc.) indicating case distribution across regions  

> 📅 Timeframe: Covers cases during the 2020–2021 pandemic periods

---

## 📈 Project Workflow

### 1. 🧹 Data Preprocessing
- Parsed and formatted dates
- Handled missing values
- Created new time-based features (e.g., Day, Week, Month)
- Converted numerical and regional data into structured formats for modeling

### 2. 🔍 Exploratory Data Analysis (EDA)
- Trend analysis of cases over time
- Heatmaps to visualize case distribution by region
- Correlation matrix to assess feature relationships

### 3. 📉 Modeling and Prediction
- **Time series forecasting** using models like:
  - Linear Regression
  - ARIMA (AutoRegressive Integrated Moving Average)
  - Decision Trees / Random Forest (optional extension)
- Model evaluation using:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)

### 4. 📊 Visualization
- Line plots of actual vs predicted cases
- Regional comparison dashboards
- Seasonal trends and peaks

---

## 💡 Key Insights

- COVID-19 spread showed **strong weekly and monthly patterns**
- Certain regions (e.g., Casablanca-Settat) consistently reported higher case loads
- Machine learning models (especially ARIMA & Linear Regression) performed well on short-term predictions
- Accurate forecasting helps simulate scenarios for public health measures

---

## 🛠️ Tools & Libraries

- **Python** (Jupyter Notebook)
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – ML modeling and evaluation
- **Statsmodels** – ARIMA time series forecasting

---

## 📎 Live Notebook

👉 [**Open the Jupyter Notebook on GitHub**](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/Project%202_Personalized%20Machine%20Learning%20COVID-19%20Cases.ipynb)

---

## 📚 Future Improvements

- Extend prediction to include hospital capacity and vaccination rates
- Incorporate **LSTM** or other deep learning models for long-term forecasting
- Build a Streamlit or Dash app to deploy interactive forecasts

---

## 👤 Author

**Faissal Elmokaddem**  
Data Science & Engineering Student | ALX Africa Program 2025

---

> 📌 This project was completed as part of a personalized ML challenge during the ALX Data Science Program.

