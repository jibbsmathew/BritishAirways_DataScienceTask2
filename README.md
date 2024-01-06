# Customer Bookings Predictive Model

This project involved developing a machine learning model to predict whether a customer will complete a flight booking based on details of their reservation.

## Data

The data used consists of 50,000 customer flight booking records with the following attributes:

- Booking details: number of passengers, sales channel, trip type, days between booking and travel
- Flight details: length of stay, departure time, day of week, route, flight duration 
- Customer preferences: extra baggage, preferred seats, in-flight meals
- Target variable: booking_complete (1 if customer completed booking, 0 otherwise)

## Analysis

The Jupyter notebook provides exploratory data analysis on the dataset including:

- Summary statistics of all numeric variables
- Visualizations for distribution of numeric and categorical features  
- Correlation analysis between numeric variables
- Analysis of relationships between features 

Key observations and hypotheses were recorded based on the analysis.

## Model Building 

A Random Forest Classification model was trained on the dataset to predict the booking_complete target variable. The steps include:

- One-hot encoding categorical variables
- Splitting data into train and test sets
- Fitting model and making predictions
- Evaluating accuracy, classification report, confusion matrix
- Identifying most important features based on model

## Recommendations

Based on model feature importance analysis, recommendations were provided to maximize bookings:

- Highlight preferred seat options to target customers likely to select
- Ensure competitive flight durations relative to route
- Focus sales efforts in highest booking origin countries

## Next Steps

Potential next steps to improve the model:

- Engineer new features combining existing variables  
- Try different models e.g. gradient boosting, SVM
- Use K-fold cross validation to evaluate model robustness
- Track and compare model accuracy on live data
