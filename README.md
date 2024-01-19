# Linear Regression Health Costs Calculator
This project is part of the Machine Learning with Python curriculum of freeCodeCamp. It aims to create a linear regression model that predicts the health insurance costs of individuals based on their age, sex, BMI, number of children, and smoking status.
## Dataset
The dataset used for this project is the Medical Cost Personal Datasets, which contains 1338 records of health insurance charges for different individuals.
## Requirements
This project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- tensorflow
This project also requires Google Colaboratory, a cloud-based platform that allows you to run Python code in a browser.
## Installation
To install this project, follow these steps:
- Clone this repository to your local machine or your Google Drive.
- Open the notebook file `linear_regression_health_costs_calculator.ipynb` in Google Colaboratory.
- Run the code cells in the notebook to import and explore the data, create the model, and test the function.
## Usage
To use this project, you can call the function `estimate_price` with a list of features as an argument. The function will return the predicted health insurance cost for the individual with those features. For example:
```python
estimate_price([[20, 1, 26, 1, 0, 1]])

Output:

3190.8708