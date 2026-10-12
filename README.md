# Hotel ADR Prediction

Predicting hotel Average Daily Rate (ADR) from 6,630 bookings to support pricing decisions. Individual assignment, Sunway University (October 2025).

## Results

| Model | RMSE | MAE | R² |
|---|---|---|---|
| Linear Regression | 41.17 | 26.24 | 0.96 |
| Random Forest | 37.87 | 20.70 | 0.96 |
| **Gradient Boosting** | **33.80** | **19.15** | **0.97** |

## Key Findings
- Strongest predictors: Competitor Average Rate, Star Rating and Review Score
- Data cleaning: standardised inconsistent text categories, removed duplicate bookings and rows with missing ADR
- Engineered features: guest nights, last-minute booking flag and customer age groups
- Total Spend, Extra Spend and Satisfaction Rating were excluded from modelling as they are only known after the stay

**Tech:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn
