
# 📊 FBI Crime Forecasting Using Time Series & ML

## 🔍 Overview
This project forecasts future crime trends across U.S. regions using FBI Uniform Crime Reporting (UCR) data. It combines time series modeling and machine learning techniques to analyze historical crime data, identify patterns, and predict future crime rates for strategic planning and policy evaluation.

## 🧠 Problem Statement
Can we predict how various categories of crime (e.g., violent crime, property crime) will evolve in future years using historical FBI crime data? Accurate forecasting can help in resource allocation and proactive crime prevention strategies.

## 🛠️ Tools & Technologies
- **Python**
  - `Pandas`, `NumPy` – Data manipulation
  - `Matplotlib`, `Seaborn` – Visualization
  - `Scikit-learn`, `XGBoost` – Machine Learning
- **Google colab**
- **FBI UCR Dataset** (CSV format )

## 📈 Methodology
1. **Data Cleaning & Preprocessing**
   - Missing value handling
   - Time formatting
   - Aggregation by year and crime category

2. **Exploratory Data Analysis**
   - Crime trends by year and state
   - Crime trend area wise
   - Barplot and line charts

3. **Modeling**
   - **ML Models**:
     - Regression models (Linear, XGBoost) to predict numeric crime counts

4. **Evaluation**
   - RMSE for regression models
   - Scatter plot evaluation and check how the two model perform
   - Forecast plots 

## 📊 Results & Insights
- Property and violent crime have shown a consistent decline post-2010.
- Used scatter plot to compare the two ml models that is xg boost and random forest
- XGBoost regression  in predicting future crime counts by category.

## 📂 Repository Structure
```
├── Fbitimeseries.ipynb         # Main notebook with full code
├── crime_data.csv              # Raw or cleaned FBI dataset (if included)

└── README.md                   # Project overview and documentation
```

## 📌 Key Takeaways
- Demonstrates how XG boost  can be applied to social datasets.
- Shows how combining ML and classical methods gives more robust forecasting.

## 🚀 Future Work
- Add interactive dashboards using **Plotly Dash** or **Power BI**.
- Train deep learning models (LSTM) for long-term forecasting.
- Include socio-economic features (like unemployment, poverty rates) for multi-variate forecasting.

## 👨‍💻 Author
**Ankit Gaurav**  
📧 ankitgaurav567@gmail.com  
[LinkedIn](https://linkedin.com/in/ankit-gaurav-18a041165) | [GitHub](https://github.com/ankitgaurav567)

