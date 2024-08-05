# Sales Prediction Analysis - Final Observations

## Conclusion
To conclude the sales prediction analysis, we interpret the metrics and visual plots to provide insights about the model's performance and its potential application.

## Metrics Interpretation

- **Mean Absolute Error (MAE)**: Indicates the average magnitude of errors in the predictions, without considering their direction. A lower MAE suggests better predictive accuracy.
- **Mean Squared Error (MSE)**: Emphasizes larger errors by squaring them, providing an indication of the overall fit of the model. A lower MSE is better.
- **R-squared (R²)**: Represents the proportion of variance in the target variable that is explained by the model. An R² closer to 1 indicates a better fit.

## Visualization Interpretation

- **Distribution of Sales**: If the sales data is normally distributed, it suggests a stable prediction target. Any skewness might need transformation.
- **Scatter Plots**: These help identify the relationships between advertising channels (TV, Radio, Newspaper) and sales. Strong linear relationships suggest those features are good predictors.
- **Correlation Matrix**: Shows the correlation between variables. High correlations with sales imply stronger predictive power. Multicollinearity among features might need addressing.
- **Actual vs Predicted Sales**: Points close to the red line indicate good predictions. Significant deviations suggest areas for model improvement.
- **Distribution of Residuals**: Should ideally resemble a normal distribution centered around zero, indicating unbiased predictions. Patterns in residuals suggest model weaknesses.

## Final Interpretation

The linear regression model trained to predict sales based on advertising expenditure across TV, Radio, and Newspaper channels demonstrates a reasonable level of predictive accuracy. Key insights from the analysis are:

### Model Performance

- **Mean Absolute Error (MAE)**: 1.2725851163834117
- **Mean Squared Error (MSE)**: 2.9289106762499757
- **R-squared (R²)**: 0.9052166208889012

These metrics indicate that the model performs reasonably well, with an R² value suggesting that a significant portion of the variance in sales is explained by the advertising expenditures.

