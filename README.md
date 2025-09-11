Project Title: “House Prices – Advanced Regression” (Kaggle Competition)

The projcet is about finding house prices based on 79 explanatory variables

the evaluation is based on  Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price

project link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

The competition’s key challenge is that submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted sale price and the logarithm of the actual sale price. This log transformation ensures that prediction errors for expensive and inexpensive homes are penalized equally, rather than allowing high-value homes to dominate the error metric.

My personal learning goal with this project is to:

Strengthen my understanding of regression models (linear models, tree-based methods, ensemble techniques).

Practice feature engineering and data preprocessing on a real-world dataset.

Explore model evaluation and hyperparameter tuning.

Build a reproducible pipeline that could serve as a portfolio project for both learning and demonstration.

Data Overview

Feature distribution: Most categorical variables are highly imbalanced (e.g., Electrical, Condition2), while numerical features like GrLivArea and LotArea show skewness.

Missing values: Several variables contain missing data (e.g., LotFrontage, Alley, FireplaceQu, GarageType). Handling these is an important step in the pipeline.
