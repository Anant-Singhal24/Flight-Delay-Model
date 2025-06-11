# Flight Delay Prediction: Enhancing Air Travel Reliability

A data-driven project that uses machine learning to predict flight delays, helping airlines improve operational efficiency and passenger experience.

## Project Overview

This project focuses on enhancing operational excellence in air travel through predictive analytics of flight delays. Using advanced machine learning models, we can accurately predict:

- Whether flights will experience significant delays
- The expected duration of delays
- Key factors contributing to delays

## Methodology

### Data Preparation

- Cleaned and structured dataset including carrier, airport, delay types, and durations
- Applied weighted analysis to controllable delays for deeper insights

### Exploratory Data Analysis

Our analysis revealed distinct trends in flight delays:

- **Seasonal Patterns**: Rainy months (July-August) show 24% higher delay rates due to weather
- **Carrier Performance**: Significant variation between carriers (15-45 min average delays)
- **Airport Congestion**: Top 5 airports account for 30% of all delays

### Primary Delay Causes

- Late Aircraft
- Carrier Issues
- National Air System
- Weather
- Security

### Modeling Strategy

- Developed regression models to predict delay duration per flight
- Compared Linear Regression, Random Forest, and Gradient Boosting
- Used SHAP values for model interpretability and feature importance

## Model Performance

### Classification Model

Our classification model predicts if over 20% of flights for a specific carrier-airport combination will be significantly delayed.

- **Accuracy**: 96.32%
- **Precision**: 99.48%
- **Recall**: 90.42%
- **F1-score**: 94.74%

### Gradient Boosting Regression

Our regression model accurately predicts total delayed flight minutes.

- **MAE**: 641.82
- **RMSE**: 1879.13
- **R² Score**: 0.9733

### Per Flight Prediction

- **MAE**: 2.44 minutes per flight
- **RMSE**: 6.08 minutes per flight
- **R² Score**: 0.9735

## Key Predictive Factors

1. Late aircraft delay (2.7x weight)
2. Carrier operations (2.1x weight)
3. Airport congestion (1.8x weight)
4. Weather conditions (1.5x weight)
5. Month/season (1.3x weight)

## Actionable Recommendations

### Schedule Optimization

- Build 15-minute buffer periods for high-risk routes (12% delay reduction potential)
- Adjust winter schedules with 8% longer connection times (20% missed connection reduction)

### Resource Management

- Implement dynamic crew scheduling based on predictive delay factors
- Position maintenance staff strategically at major hubs during peak hours

### Communication Strategy

- Develop early notification system triggered by model predictions
- Implement automated rebooking options for passengers on high-risk flights

## Next Steps

1. **Detailed Methodology**: Explore our data preparation and modeling techniques
2. **Complete EDA Results**: Dive into all findings from our exploratory data analysis
3. **Model Comparison Details**: Review the performance of various models considered
4. **Implementation Roadmap**: Understand how these solutions can be integrated

## Author

Anant Singhal  


