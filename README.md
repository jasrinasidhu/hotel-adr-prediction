# Hotel ADR Prediction

Machine learning project to predict hotel Average Daily Rate (ADR) using booking and customer data, helping hotels make data-driven pricing decisions.

Completed as an individual assignment for BAA5053 – Machine Learning for Business Decisions at Sunway University (October 2025).

## Model Results

| Model | RMSE | MAE | R² |
|---|---|---|---|
| Linear Regression | 17.85 | 5.61 | 0.99 |
| Random Forest | 8.21 | 2.84 | 1.00 |
| **Gradient Boosting (tuned)** | **6.35** | **1.76** | **1.00** |

**Gradient Boosting** was the best-performing model after hyperparameter tuning with GridSearchCV.

## Key Findings
- Strongest predictors of ADR: Competitor Average Rate, Star Rating, Total Spend, and Review Score
- Hotels with higher prices tend to have stronger competition, better ratings, and higher-spending guests
- Last-minute bookings (≤7 days) and guest nights were engineered as additional features to improve accuracy

## Tech Stack
Python, Scikit-learn, Pandas, Matplotlib, Seaborn, GridSearchCV

## Files
| File | Description |
|---|---|
| `machine_learning_assignment.ipynb` | Full notebook (EDA, feature engineering, modelling) |
| `Hospitality_Wrangling_EDA_Regression.csv` | Dataset used |
