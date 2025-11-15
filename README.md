# Student Performance Prediction

Linear Regression model to predict exam scores based on study hours.

## Dataset
Student Performance Factors (Kaggle)

## Features
- Data cleaning & visualization
- Linear regression model
- Model evaluation (R², RMSE, MAE)
- Saved model for reuse

## Usage
```python
import joblib
model = joblib.load('student_performance_model.joblib')
score = model.predict([[20]])  # 20 study hours
```

## Results
- R² Score: [Your score here]
- RMSE: [Your RMSE here]
- MAE: [Your MAE here]
