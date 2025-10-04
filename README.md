# Housing Price Prediction Mini-Project

## Project Structure
- 'house_prices_cv.ipynb': Main notebook
- 'train.csv': Housing prices data

## Goals
- Implement and compare Linear Regression, Ridge Regression, and Lasso Regression
- Use proper preprocessing piplines with numerical scaling and categorical encoding
- Model evaluation using cross-validation

## Results
- Ridge Regression achieved better validation performance from cross-validation
- Linear regression surprisingly outperformed Ridge on the test set
- Suggests that Ridge Regression's default alpha parameter might have been too aggressive, causing underfitting despite preventing overfitting.

## Next Steps
- Hyperparameter Tuning: Implement grid search or random search for param tuning
- Model comparison: Re-evaluate all models with tuned hyperparams on the test set
- Feature engineering
- Advanced models like Random Forest and XGBoost
- Error analysis: What's causing errors?