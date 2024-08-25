House Price Prediction using Linear Regression
Overview:
This repository contains a Python implementation of a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms. The model is trained on the House Prices: Advanced Regression Techniques dataset from Kaggle.

Dataset:
The dataset used in this repository is the House Prices: Advanced Regression Techniques dataset from Kaggle. The dataset contains 1460 samples with 79 features, including the target variable SalePrice.

Features used:
The following features are used in the linear regression model:

GrLivArea: Above grade (ground) living area square feet
BedroomAbvGr: Number of bedrooms above grade (ground)
FullBath: Number of full bathrooms

Model
The linear regression model is implemented using the LinearRegression class from scikit-learn. The model is trained on the training data and evaluated using the mean squared error (MSE) metric.

Results
The performance of the model is evaluated using the mean squared error (MSE) metric. The MSE score is calculated using the mean_squared_error function from scikit-learn.

License
This repository is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! If you'd like to contribute to this repository, please fork the repository, make your changes, and submit a pull request.
