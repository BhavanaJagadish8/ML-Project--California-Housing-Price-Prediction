# ML-Project--California-Housing-Price-Prediction

The provided code performs various tasks related to data preprocessing, regression modeling, and visualization using the pandas, numpy, matplotlib, and scikit-learn libraries in Python. Here's a breakdown of the code:

1. Importing Required Libraries:
   - pandas: Library for data manipulation and analysis.
   - numpy: Library for mathematical operations.
   - matplotlib.pyplot: Library for data visualization.

2. Reading Data:
   - The code reads the 'housing.csv' file using pandas' `read_csv` function and stores it in the `Housing` dataframe.
   - The first few rows of the dataframe are printed using the `head()` function.

3. Data Preprocessing:
   - Extracting input features (X) and the output variable (Y) from the dataset.
   - Handling missing values by filling them with the mean of the respective column.
   - Converting categorical columns into numerical data using one-hot encoding.
   - Splitting the data into training and test sets using the `train_test_split` function from scikit-learn.
   - Standardizing the training and test datasets using `StandardScaler` from scikit-learn.

4. Linear Regression Modeling:
   - Performing linear regression on the training data using `LinearRegression` from scikit-learn.
   - Predicting the output for the test set and calculating the root mean squared error (RMSE).
   - Printing the RMSE for linear regression.

5. Decision Tree Regression Modeling:
   - Performing decision tree regression on the training data using `DecisionTreeRegressor` from scikit-learn.
   - Predicting the output for the test set and calculating the RMSE.
   - Printing the RMSE for decision tree regression.

6. Random Forest Regression Modeling:
   - Performing random forest regression on the training data using `RandomForestRegressor` from scikit-learn.
   - Predicting the output for the test set and calculating the RMSE.
   - Printing the RMSE for random forest regression.

7. Linear Regression with One Independent Variable:
   - Extracting the 'median_income' column from the training and test sets.
   - Creating a linear regression object and fitting the model on the training data.
   - Predicting the output for training and test data.
   - Plotting the fitted model for training and test data using matplotlib.

The code demonstrates the steps involved in data preprocessing, building regression models, and evaluating their performance. It also includes visualizations to understand the relationship between variables.
