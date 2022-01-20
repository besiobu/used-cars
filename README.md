# used-cars
Predicting used car prices.

### Project goal
The goal of this project is to test the performance of various models in the task of predicting prices of used cars.

### Methods
* Machine learning
* Neural networks
* Decision trees
* Regularization
* Boosting

### Technologies
* Python
* Scikit-lean
* LightGBM
* XGBoost

### Project description
A dataset of 400k cars for sale on craigslist was obtained from [Kaggle](https://www.kaggle.com/austinreese/craigslist-carstrucks-data). The data was then massaged into a useable state.
Circa half of the dataset did not meet the neccesary requirements due to reasons such as missing values, outliers or rare car manufacturers (eg. Porsche).
The next step was to use a baseline model. After that I used different techniques to try to forecast the prices of cars. This includes regressions, trees and neural networks. The models where selected using grid search on basic parameter grid. 10 fold cross validation was used.

### Analysis and notebooks
A writeup of my findings can be obtained by viewing the [`11-summary`](https://github.com/besiobu/used-cars/blob/main/notebooks/11-summary.ipynb) notebook.
![image](https://github.com/besiobu/used-cars/blob/main/reports/figures/results.png)
