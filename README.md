# 🚲Predicting Registered Capital Bikeshare™ Users with Exponential Smoothing

This was the final project for MDS-620 Data-Driven Decision Making during the Spring of 2025. It uses a compilation of some publicly-available datasets and demonstrates several visualization techniques.

---

## 🔭 Project Summary

An analysis of user behavior and weather patterns to predict the number of registered users during a given timeframe.
- Data Visualization
- Linear Regression
- Lasso Regression
- Ridge Regression
- Exponential Smoothing

The optimal outcome is a model that accurately predicts the **number of registered users** for January 2013 based on data from 2011 and 2012.

---

## ⚙️ Tools
- 🐼 **Pandas**
- #️⃣ **Numpy**
- 📊 **Matplotlib**
- 🤖 **Sklearn**
- ⛏️ **DMBA**
- 📉 **Statsmodel**

---

## 📂 Dataset 

The dataset is called `day.csv` and is compilation of data from the multiple sources. It includes weather information, and user counts are aggregated on a daily basis. The data book provides details regarding the sources of the data and how it was transformed.

💾 [Download the Dataset](day(1).csv)

📖 [Download the Data Book](bike_sharing_data_book.pdf)

### Features
- 📅 Date
- 🍂 Season
- 🍾 Year
- 🌒 Month
- 🎄 Holiday
- ☀️ Weekday (day of the week)
- 💼 Workingday (1/0)
- ☁️ Weather Situation
- 🌡️ Temperature
- 🌡️ Feeling Temperature
- 🍃 Windspeed
- 🏖️ Casual Users (count)
- ®️ Registerd Users (count)
- 🌐 Total Users (count)

---

## 💡 Key Insights
- The data showed clear seasonality, thus the need for exponential smoothing.
- The model's predictions for January 2013 were consistent with the counts for January of 2011 and 2012.
- Stakeholders can use this model to increase registered users in order to gain access to the wealth of data that registration brings.

--- 

## 🏃 Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/jacanevaro/data_visualization_project.git
   cd data_visualization_project
---

* I used the Copilot AI integration in Bing to help me find the right grapics to use in this .README file.
