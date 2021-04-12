# NYC-Airbnb-Data-Product
Data analysis, visualization, and prediction on NYC Airbnb data

## Description

This project analyzes Airbnb data gathered from the New York City area in 2019, the listingg in the data range from private residences to rooms, neighbourhoods, neighbourhood groups, prices, and etc. The goal of this project is to create a model that can predict future AirBnb prices as well as which neighbourhoods of the city are most profitable.

## Data Source

This public dataset is part of Airbnb, and the original source can be found on this [website](http://insideairbnb.com/).
It contains a mix of qualitative and quantitative data, with 48,895 entries and 16 columns.
Our model will consist of 34,218 entries for training and 14,666 for testing the target label PRICE.

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

## Contributors

* [Michael Oceguera](https://github.com/syntaxmike)
* [sean ybarra](https://github.com/seanybarra)
* [Kevin Crespin](https://github.com/KevinCrespin)


