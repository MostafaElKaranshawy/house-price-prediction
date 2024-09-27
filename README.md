# House Price Prediction

This notebook predicts house prices using a machine learning model based on various features in the dataset. Below is a summary of the steps, operations, and libraries used.

## Libraries Used
- `pandas`: For data manipulation and cleaning.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `sklearn.linear_model`: For the linear regression model.
- `sklearn.metrics`: For evaluating model performance.

## Workflow

### 1. Data Preprocessing
The notebook starts by loading and preprocessing the dataset:
- The `train.csv` and `test.csv` files are read using `pandas`.
- Unnecessary columns, such as `Id`, are dropped.
- Numerical columns are selected and missing values are filled with the mean of each column.

### 2. Data Preparation
- **Training Data**: Numerical features from the training data are selected. The target variable is `SalePrice`.
- **Test Data**: The numerical features are also selected from the test data, and missing values are filled.

### 3. Model Training
A **Linear Regression** model is used for training:
- The model is trained on the preprocessed training data (`X_train` for features and `y_train` for the target variable).

### 4. Evaluation
After training, the notebook evaluates the model by:
- Calculating the model's performance using metrics like **Root Mean Squared Error (RMSE)**.

## Steps to Run the Notebook
1. Ensure all the required libraries (`pandas`, `numpy`, `matplotlib`, `sklearn`) are installed.
2. Place the `train.csv` and `test.csv` files in the correct directory (`./dataset`).
3. Run the notebook step-by-step to preprocess the data, train the model, and predict house prices.

## Output
The notebook outputs the predicted house prices based on the test data and evaluates the model's performance using RMSE.

---
