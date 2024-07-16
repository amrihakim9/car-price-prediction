## Project Description: Car Price Prediction

### Objective:
1. Develop a model to predict car prices.
2. Evaluate the model's performance.
3. Save the trained model for future use.
   
### Business Problem (SMART Framework):
1. Specific: Accurately determine car prices.
2. Measurable: Reduce shipping costs by 15% within 6 months.
3. Achievable: Increase car sales by 10% within 1 year.
4. Relevant: Ensure car prices align with the market to enhance competitiveness.
5. Time-bound: Achieve the target within 1 year.

### Data Source:
- Dataset from Kaggle: [Car Price Dataset](https://www.kaggle.com/datasets/imgowthamg/car-price/data)
  
### Steps:
1. **Data Loading and Exploration**:
   - Load the dataset and explore its structure and summary statistics.
   - Visualize the top 10 highest car prices and scatter plots for various features.
2. **Data Cleaning**:
   - Remove unnecessary columns and handle missing values.
   - Identify and handle outliers in numerical features using winsorization.
3. **Feature Engineering**:
   - Separate numerical and categorical features.
   - Perform frequency encoding for categorical features.
   - Scale numerical features and apply one-hot encoding to categorical features.
4. **Model Development**:
   - Split the data into training and testing sets.
   - Define and evaluate multiple regression models (Linear Regression, Decision Tree Regressor, Random Forest Regressor).
   - Perform hyperparameter tuning for the best model (Random Forest Regressor).
5. **Model Evaluation**:
   - Evaluate the models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
   - Select the best model based on evaluation metrics.
6. **Model Saving and Loading**:
   - Save the trained model using [joblib](https://github.com/amrihakim9/car-price-prediction/car_pred.ipynb).
   - Load the saved model and verify its performance on the test data.

### Conclusion:
1. The Random Forest Regressor model was successfully trained to predict car prices.
2. The model's predictions are close to the actual car prices, indicating good performance.
3. The model was saved and successfully reloaded, demonstrating the ability to save and reuse the model.
4. The evaluation metrics of the reloaded model are consistent with the original model, confirming its reliability.
5. This project provides a solid foundation for further improvements and refinements in car price prediction models.
