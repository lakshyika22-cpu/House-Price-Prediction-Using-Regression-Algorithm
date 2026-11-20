# House-Price-Prediction-Using-Regression-Algorithm
Implemented and compared Simple Linear Regression, Polynomial Regression, and Multiple Linear Regression models using the USA Housing dataset to predict house prices and evaluate their performance using R² scores.

A machine learning project focused on predicting house prices using the USA Housing dataset. This project implements and compares three regression algorithms to understand their performance and prediction capabilities.

## Algorithms Implemented

1. **Simple Linear Regression** - Predicts house prices using Area Income as a single independent variable.
2. **Polynomial Regression** - Uses degree 2 polynomial features to model a potentially curved relationship between Area Income and Price.
3. **Multiple Linear Regression** - Predicts house prices using five independent variables:
   - Area Income
   - Area House Age
   - Area No of Rooms
   - Area No of Bedrooms
   - Area Population

## Dataset

USA Housing Dataset (`USA_Housing.csv`)

**Target Variable:** Price

## Model Training

- Training Data: 80%
- Testing Data: 20%
- Random State: 0

## Model Performance

| Algorithm | R² Score |
|---|---:|
| Simple Linear Regression | 0.4006 |
| Polynomial Regression | 0.4017 |
| Multiple Linear Regression | 0.7340 |

Multiple Linear Regression achieved the highest R² score among the three implemented models.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Files

- Python notebook / source code
- USA Housing dataset (if included)
- Project presentation (PPT)

## Learning Outcomes

- Understanding different regression algorithms.
- Working with a real-world housing dataset.
- Training and testing machine learning models.
- Evaluating model performance using R² scores.
- Comparing single-feature and multiple-feature regression models.
