# Hotel ADR Prediction

Predicting hotel Average Daily Rate (ADR) from 6,630 bookings to support pricing decisions. Individual assignment, Sunway University (October 2025).

## Results

| Model | RMSE | MAE | R² |
|---|---|---|---|
| Linear Regression | 44.22 | 27.85 | 0.95 |
| Random Forest | 36.08 | 21.50 | 0.97 |
| **Gradient Boosting** | **36.05** | **20.84** | **0.97** |

## Key Findings
- Strongest predictors: Competitor Average Rate, Star Rating, Total Spend and Review Score
- Engineered features: guest nights, last-minute booking flag and customer age groups

**Note:** Total Spend partly includes the room rate, which inflates R². Next step is to remove it and re-run.

**Tech:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn
