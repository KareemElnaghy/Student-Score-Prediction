# Student Score Prediction

## Introduction
This project predicts student exam scores using linear and polynomial regression models based on hours studied.

## Features
- Data import and preprocessing
- Exploratory data analysis (correlation heatmap, scatter plots)
- Linear regression model training and evaluation
- Polynomial regression model training and evaluation
- Model comparison and visualization

## Dataset Information
- Source: KaggleHub (`lainguyn123/student-performance-factors`)
- Features used: `Attendance`, `Previous_Scores`, `Hours_Studied`, `Exam_Score`
- Format: CSV

## Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- kagglehub

Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn kagglehub
```

## Model Evaluation Results

| Model                 | Mean Squared Error (MSE) | Mean Absolute Error (MAE) | R-squared |
|-----------------------|-------------------------|---------------------------|-----------|
| Linear Regression     | *10.856*                 | *2.448*                   | *0.232*   |
| Polynomial Regression | *10.856*                 | *2.448*                   | *0.232*   |

## Results and Discussion
- The output of the project showed model evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE) and R-squared.
- Plots comparing actual vs. predicted exam scores for both models.
- Model was trained using only one feature, hours studied, but other features such as the Attendance and Previous Scores showed a positive correlation with Exam Score.
- Linear Regression: Achieved reasonable accuracy, indicating a mostly linear relationship between features and exam scores.
- Polynomial Regression: Performance was similar to linear regression, suggesting limited non-linear patterns in the data.
- Comparison: Both models yielded the same results, confirming that the dataset is well-approximated by a linear function. Visualization plots show minimal improvement with polynomial features.
