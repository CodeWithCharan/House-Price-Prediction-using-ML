## ML-Project-1

### Software and Tools Requirements

1. [GitHub Account](https://github.com/)

2. [Python](https://www.python.org/downloads/)

3. Jupyter Notebook

	```
	pip install jupyter notebook
	```

4. Modules
	- pandas
	```
	pip install pandas
	```

	- Numpy
	```
	pip install numpy
	```

	- Matplotlib
	```
	pip install matplotlib
	```

	- SKlearn
	```
	pip install scikit-learn
	```

## Documentation

### I. Introduction
- One Piece Real Estate is a real estate company that is facing a challenge in predicting the prices of houses. In this project, we aim to help the company by building a Machine Learning model that can accurately predict the prices of houses based on a set of features.

### II. Data Collection
- we have collected Boston Housing Data, 
  - Origin:  This dataset was taken from the StatLib library which is
             maintained at Carnegie Mellon University.
  - Creator:  Harrison, D. and Rubinfeld, D.L. 'Hedonic prices and the 
                 demand for clean air', J. Environ. Economics & Management,
                 vol.5, 81-102, 1978.
  - Date: July 7, 1993 [Click on this link for datasets](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/)
- We cleaned the data by filling in missing values where possible(0, mean, or median).

### III. Data Exploration and Analysis
- We used a variety of techniques to explore the data and identify promising attributes for our model. For example, we created scatterplots and histograms to visualize the distribution of different variables, and calculated correlation coefficients to identify variables that were highly correlated with the target variable (i.e., house price).

### IV. Model Selection and Development
- After exploring the data, we selected the Random Forest Regression algorithm as the best option(also tried LinearRegression and DecisionTreeRegressor) for building our predictive model. We used the scikit-learn library to develop the model, which we trained and optimized using a combination of cross-validation, and train-test splitting.

- Our final model was achieved and then we started Saving the model using Joblib, Testing the model on test data, and Using the model.

### V. Conclusion
- In conclusion, this project demonstrates the power of Machine Learning in predicting house prices. We have developed a model that can accurately predict house prices based on a variety of features, which can help One Piece Real Estate.
