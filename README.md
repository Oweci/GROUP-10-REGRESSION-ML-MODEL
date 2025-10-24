GROUP-10-REGRESSION-ML-MODEL  "Traffic Volume Prediction using Machine Learning"
We are trying to create a ML model that can detect Traffic at cross road 6

GOAL
To develop a predictive model that estimates traffic volume at a junction using data from surrounding intersections and factors like weekday patterns and time.

DATASET
Name:traffic_dataset_with_weekdays.xlsx  
Our data has 11,519 rows and 8 columns  
Features:
  - Cross_1, Cross_2, Cross_3, Cross_4, Cross_5 — traffic volumes at nearby intersections  
  - Weekday — day of the week
  - Timestamp  
  
Target Variable:
Cross_6 (traffic volume at the target junction)

Machine Learning Models Used
1. Linear Regression- baseline model for understanding basic correlations
2. decision tree regressor

Visualizations
- Traffic distribution by weekday  
- Actual vs Predicted scatter plot  
- Feature importance ranking (Random Forest)
- Univariate Visualization : Histogram
- Multivariate Visualization : Grouped Bar chart 


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

