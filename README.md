GROUP-10-REGRESSION-ML-MODEL  "Traffic Volume Prediction using Machine Learning"
We are trying to create a ML model that can detect Traffic at cross road 6

GOAL
To develop a predictive model that estimates traffic volume at a junction using data from surrounding intersections and factors like weekday patterns and time.

DATASET
Name:traffic_dataset_with_weekdays.xlsx  
16,128 (after cleaning and adjustments)  
Features:
  - Cross_1, Cross_2, Cross_3, Cross_4, Cross_5 — traffic volumes at nearby intersections  
  - Weekday — day of the week (Monday–Sunday)  
  
Target Variable:
Cross_6 (traffic volume at the target junction)

Machine Learning Models Used
1. Linear Regression- baseline model for understanding basic correlations
2. decision tree regressor

Evaluation Metrics
1.Coefficient of Determination (R² score)-It measures how well the model’s predictions fit the actual data.
2.Mean Absolute Error (MAE)-It measures the average magnitude of errors in your predictions — without considering direction
3.Mean Squared Error (MSE)-It measures the average of the squared differences between actual and predicted values.

Visualizations
- Traffic distribution by weekday  
- Correlation heatmap between junctions  
- Actual vs Predicted scatter plot  
- Feature importance ranking (Random Forest)  


Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


Authors
1.Nabukenya Florence
2.Sisco Cherop
3.Salha Oweci

