## Project Description: Car Price Prediction

### Objective:
1. Develop a model to predict car prices.
2. Evaluate the model's performance.
3. Save the trained model for future use.
   
### Business Problem (SMART Framework):
To ensure car prices align with the market and enhance competitiveness, I aim to accurately determine car prices, increase car sales by 10%, and reduce shipping costs by 15% within 1 year.

### Data Source:
- Dataset from Kaggle: [Car Price Dataset](https://www.kaggle.com/datasets/imgowthamg/car-price/data)
- About: This dataset contains information about different car models, with attributes such as insurance risk rating, car company, fuel type, aspiration, number of doors, body style, drive wheel type, engine location, dimensions (wheelbase, length, width, height), weight, engine type, cylinder count, engine size, fuel system, engine specifications (bore ratio, stroke, compression ratio, horsepower, peak RPM), and mileage (city and highway). The goal could be to analyze or predict the car's price based on these attributes.
  
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
   - Save the trained model using joblib.
   - Load the saved model and verify its performance on the test data.

### Conclusion:
1. The Random Forest Regressor model was successfully trained to predict car prices.
2. The model's predictions are close to the actual car prices, indicating good performance.
3. The model was saved and successfully reloaded, demonstrating the ability to save and reuse the model.
4. The evaluation metrics of the reloaded model are consistent with the original model, confirming its reliability.
5. This project provides a solid foundation for further improvements and refinements in car price prediction models.
