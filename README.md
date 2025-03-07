# Linear Regression Model

This repository contains a Linear Regression model implemented from scratch in Python. The model is trained on the `auto-mpg` dataset to predict the mileage per gallon (mpg) of cars based on various features such as cylinders, displacement, horsepower etc.

## Project Overview
-------------------

- **Dataset**: The `auto-mpg` dataset is used, which includes features about cars and their corresponding mileage per gallon (mpg).normalization, and model training.
- **Features**:
  - Cylinders
  - Displacement
  - Horsepower
  - Weight
  - Acceleration
  - Model Year
  - Origin

## Usage
--------

1. Clone the repository: `git clone https://github.com/Dhruv2676/Linear-Regression.git`
2. Install the required packages: `pip install requirements.txt`

3. Run the model:
- Open the `Linear-Regression.ipynb` file in Jupyter Notebook or Google Colab.
- Execute the cells to load the data, preprocess it, train the model, and visualize the results.

## Model Details
----------------

- **Data Preprocessing**:
    - Handling missing values by dropping rows with NaNs.
  - Converting categorical data into numerical format where necessary.
  - Feature scaling using Z-Score normalization to ensure all features are on the same scale.

- **Model Training**:
  - The Linear Regression model is trained using the scaled features.
  - The model predicts the mileage per gallon (mpg) based on the input features.
  - Grid Search for hyperparameter tuning.

## Future Improvements
----------------------

- **Model Evaluation**: Incorporating other types of cost functions and letting the user choose which one to use.
- **Feature Engineering**: Exploring additional features that could improve model accuracy.

## License
-------

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
----------------

The `auto-mpg` dataset is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/auto+mpg).
