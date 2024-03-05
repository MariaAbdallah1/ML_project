# project Description Document

## General Information on dataset:
* Name of dataset (Car details v3). 
*	Labeled by selling_price. 
*	Number of samples in dataset 8128. Train to test ratio is 80% to 20% which is 6502 to 1626 and validation is 1084. 

## Implementation details:
* Dimension of features is 11 which are (name, year, selling_price, km_driven, fuel, seller_type, transmission, owner, mileage, engine, max_power, torque, seats).
*	Number of fold is 6 and ratio of training to validation is 5 to 1.
*	Hyperparameters used are n_splits in KFold = 6 and n_neighbors in KNeighborsRegressor = 3

## Results details:
*	Linear Regression model: r2.score = 57.9%, rmse = 160637. Polynomial Regression with degree 2: r2.score = 70%, rmse = 137513.98.
*	KNN model: r2.score = 77% 

![image](https://github.com/MariaAbdallah1/ML_project/assets/151842825/77c705d4-3b58-4145-8237-6d2573906851)

![image](https://github.com/MariaAbdallah1/ML_project/assets/151842825/27853824-7c70-4025-8f4c-178cc34f6add)

