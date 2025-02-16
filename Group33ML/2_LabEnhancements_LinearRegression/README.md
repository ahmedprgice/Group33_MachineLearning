## Overview of the Process and Results:
We trained a linear regression model to predict house prices based on features like area, number of bedrooms, bathrooms, and other house attributes. The model uses past data to find relationships between these features and the price of the house.


---

## Key Results:
*   R-squared (0.643): This means the model explains 64.3% of the variation in house prices. It’s a decent fit but could be improved with additional features.
house prices. It’s a decent fit but could be better.
*   P-values:Some features, like area, bathrooms, and stories, are important predictors of price. Others, like guestroom, might not be as significant.
*   For each unit increase in area, the price increases by 702,600.
More bedrooms, bathrooms, parking spaces, or stories also increase the price significantly.

## Model Evaluation:
*   MAE (921,450.32): On average, the model’s predictions are off by about 921,450. Lower values indicate better accuracy.
*   RMSE (1.33e+06): The root mean squared error shows that typical errors are around 1.33 million, highlighting some large deviations.
*   R-squared Score on Test Data (0.649): The model explains 64.9% of price variance in unseen data, slightly lower than the training R², indicating mild overfitting.

## Visualizations:
*   Prediction vs Actual: We plotted the predicted prices against actual prices. The closer the points are to the red line, the better the predictions.
*  Residuals vs Predicted: This shows how well the model’s errors (residuals) match up with predictions. The more random the errors, the better.

## Conclusion:
The model works reasonably well, explaining a good portion of the price variation. However, it could be improved with more data or a different model.
The error metrics (MAE and MSE) show that the predictions could be more accurate.

## REFERENCE
[Ashish]. (2019). [Housing Dataset], [Version 1], https://www.kaggle.com/datasets/ashydv/housing-dataset