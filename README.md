# NYC-Airbnb-Data-Product
Data analysis, visualization, and prediction on NYC Airbnb data

## Description

In this project we analyze Airbnb data gathered from the New York City area in 2019 and create various models to predict future AirBnb prices.

## Data Source

This [datset](http://insideairbnb.com/) contains 48,895 entries and 16 columns of qualitative and quantitative data.
Our models consist of 34,218 entries for training and 14,666 for testing.

## Results

| Model  | RSME Average | 10-Fold RSME Average |
| ------------- | ------------- |------------- |
| Linear Regression  | 0.495  | 0.498  |
| Random Forest Regressor  | 0.493  | 0.509  |
| XgBoost  | 0.473  | NaN  |
| Lasso Regression  | 0.693  |  0.698  |

| Model  | Accuracy |
| ------------- | ------------- |
| Random Forest Classifier  | 83.4%  |
| Logistic Regression  | 84.5% **(Overall Best)**  |
| Decision Tree  | 80.9%  |
| KNN  | 84.1% **(when k = 15)**  |

| NYC Borough  | Average Listing price (USD) |
| ------------- | ------------- |
| Manhattan  | $291.38  |
| Staten Island  | $277.62  |
| Brooklyn  | $186.87 |
| Queens  | $167.10  |
| Bronx  | $106.70  |

## Technologies Used

* Python 
* Sklearn
* Numpy
* Matplotlib
* Pandas
* Jupyter Notebook

## Contributors

* [Michael Oceguera](https://github.com/syntaxmike)
* [sean ybarra](https://github.com/seanybarra)
* [Kevin Crespin](https://github.com/KevinCrespin)


