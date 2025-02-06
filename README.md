# Gold Mining - Data Regression
We prepared a prototype of a machine learning model for a company that develops efficiency solutions for heavy industry. The model should predict the amount of gold recovered from gold ore, given the data on extraction and purification.


## To Run

1) Clone the project
```
git clone https://github.com/filzamazahir/GoldMining-DataRegression.git
```
Make sure to have pandas, numpy, scikit-learn, and matplotlib libraries installed.

Run ```goldmining_regression.ipynb```


## Results
The three models that were trained were Random Forest, Linear Regression, and Decision Tree Regressor. Linear Regression model was chosen as it had the lowest mean absolute error between the three models. The final sMAPE value with the chosen model was 7.744 for the training set, and 9.151 for the test set, showing it worked similarly on both.
