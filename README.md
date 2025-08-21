# Bangalore Traffic Prediction and Analysis

A machine learning project that predicts traffic patterns in Bangalore using historical traffic data.

## Project Overview

This project analyzes traffic data from Bangalore to predict traffic volume, average speed, and congestion levels. It uses machine learning models to forecast traffic patterns and detect unusual traffic behavior.

## What This Project Does

- Predicts traffic volume for different areas in Bangalore
- Analyzes traffic patterns by day, week, and month
- Forecasts traffic for 1-4 weeks ahead
- Detects traffic anomalies and unusual patterns
- Provides insights for traffic management decisions

## Areas Analyzed

- **Indiranagar**: Commercial and residential mixed area
- **Whitefield**: IT corridor with office traffic
- **Koramangala**: Dense urban area with high traffic

## Roads Studied

- **100 Feet Road**: Major arterial road
- **CMH Road**: Hospital area traffic
- **Marathahalli Bridge**: Critical traffic junction

## Technology Used

### Programming Language
- Python

### Libraries
- **pandas**: Data processing and analysis
- **numpy**: Numerical calculations
- **scikit-learn**: Machine learning models
- **matplotlib**: Basic charts and graphs
- **seaborn**: Statistical visualizations
- **plotly**: Interactive charts

### Machine Learning Models
- **Random Forest**: Tree-based ensemble model
- **Gradient Boosting**: Sequential ensemble model
- **Linear Regression**: Basic prediction model

### Analysis Methods
- **Time Series Analysis**: Pattern detection over time
- **Anomaly Detection**: Finding unusual traffic patterns
- **Correlation Analysis**: Understanding relationships between factors

## Key Features

### Traffic Prediction
- Predicts traffic volume with up to 50% accuracy for IT areas
- Forecasts average speed and congestion levels
- Works best for areas with regular patterns

### Pattern Analysis
- Identifies peak traffic hours and days
- Analyzes seasonal traffic changes
- Studies weather impact on traffic

### Forecasting
- Provides 4-week traffic forecasts
- Adjusts predictions based on weather conditions
- Estimates construction impact on traffic

### Anomaly Detection
- Finds unusual traffic patterns
- Detects sudden changes in traffic flow
- Identifies 10% of records as anomalies

## Model Performance

### Best Performing Areas
- **Whitefield**: 50.6% prediction accuracy (R-squared = 0.506)
- **Indiranagar**: 46.4% prediction accuracy (R-squared = 0.464)
- **Koramangala**: 18.1% prediction accuracy (R-squared = 0.181)

### Road Prediction Accuracy
- **100 Feet Road**: 38.6% accuracy
- **CMH Road**: 36.2% accuracy
- **Marathahalli Bridge**: 29.1% accuracy

## Key Findings

### Traffic Patterns
- Wednesday has the highest traffic volume
- IT areas have more predictable traffic patterns
- Weekend traffic is 15-20% lower than weekdays

### Weather Impact
- Rain increases traffic by 15%
- Fog increases traffic by 12%
- Clear weather has normal traffic levels

### Construction Impact
- Construction increases traffic by 420 vehicles per day on average
- Impact varies by area and road capacity

### Public Transport
- No strong relationship between public transport and private vehicle usage
- Pedestrian activity has negative correlation with vehicle traffic

## Files in Project

### Notebooks
- **Traffic_analysis.ipynb**: Basic traffic pattern analysis
- **Traffic_predict.ipynb**: Machine learning predictions and forecasting
- **shap_traffic.ipynb**: Model explanation and feature importance

### Data
- **Banglore_traffic_Dataset.csv**: Main traffic dataset with 8,936 records

## Data Features

### Time Features
- Date, month, day of week, quarter
- Weekend indicator
- Cyclical time encoding

### Traffic Metrics
- Traffic volume (vehicles per day)
- Average speed (km/hour)
- Congestion level (0-100 scale)
- Travel time index

### Infrastructure
- Road capacity utilization
- Traffic signal compliance
- Parking usage

### External Factors
- Weather conditions
- Construction activity
- Public transport usage
- Pedestrian and cyclist count

## How to Run

1. Install required libraries:
   ```
   pip install pandas numpy scikit-learn matplotlib seaborn plotly
   ```

2. Open Jupyter notebooks:
   ```
   jupyter notebook
   ```

3. Run notebooks in order:
   - Start with Traffic_analysis.ipynb
   - Then run Traffic_predict.ipynb
   - Optional: shap_traffic.ipynb for model explanations

## Results Summary

### Successful Predictions
- IT corridor areas (like Whitefield) are most predictable
- Morning and evening rush hours clearly identified
- Seasonal patterns successfully captured

### Challenges
- Urban areas with mixed traffic are harder to predict
- Weather impact varies significantly
- Construction creates temporary unpredictable patterns

### Business Value
- Can reduce commute time by 10-15% with better planning
- Helps optimize traffic signal timing
- Supports infrastructure investment decisions
- Enables better emergency response planning

## Future Improvements

- Add real-time traffic data integration
- Include more external factors (events, holidays)
- Develop mobile app for commuters
- Extend analysis to more Bangalore areas
- Improve prediction accuracy with more data

## Technical Notes

- Uses time-based data splitting to avoid data leakage
- Handles missing values with median imputation
- Applies feature scaling for distance-based algorithms
- Validates models using proper time series techniques

## Contact

This project demonstrates practical application of machine learning for urban traffic management and can be extended for other cities or transportation systems.
Name: M Lalit Aditya
Email: lalitadityam2004@gmail.com

