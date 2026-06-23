# Uber Ride Cancellation Prediction

## Project Overview
Predicts whether a customer will cancel an Uber ride using Machine Learning.

## Project Structure
- Day 1 → Dataset Understanding + Preprocessing
- Day 2 → Exploratory Data Analysis (EDA)
- Day 3 → Feature Engineering + Data Preparation
- Day 4 → Model Building + Evaluation

## Dataset
- Source: Kaggle — NCR Ride Bookings
- Records: 150,000 rows
- Features: 21 columns

## Models Used
- Logistic Regression
- Random Forest  ← Best Model (96.64% Accuracy)
- XGBoost

## Results
| Model | Accuracy | R²-AUC |
|-------|----------|--------|
| Logistic Regression | 71.12% | 0.7626 |
| Random Forest | 96.64% | 0.9624 |
| XGBoost | 88.43% | 0.9646 |

## Libraries Used
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost

## Outcome
Predicts ride cancellation with 96.64% accuracy using Random Forest.
