# ecommerce-sale-prediction

In this PySpark-based model for predicting e-commerce sales, three regression algorithms have been trained, and we will select the best model among them. Here's a short prediction using the best model:

Linear Regression (regressor):
        A straightforward linear regression model.
        Trained on 'train_data' to predict 'Yearly Amount Spent' based on 'Independent Features'.

Random Forest Regression (rf_model):
        A Random Forest regression model.
        Trained on 'train_data' with specific hyperparameters.
        Predicts 'Yearly Amount Spent' using 'Independent Features'.

Decision Tree Regression (dt_model):
        A Decision Tree regression model.
        Trained with a specified maximum depth.
        Predicts 'Yearly Amount Spent' based on 'Independent Features'.

To select the best model out of these, you can typically evaluate them using metrics like Mean Squared Error (MSE) or R-squared (R2) on a validation dataset. After evaluation, choose the model with the lowest MSE or the highest R2, as it indicates the best predictive performance.
