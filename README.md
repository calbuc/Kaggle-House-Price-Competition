# House Price Prediction (Kaggle Competition)
Built for the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition.

The goal of the project is to predict the sales price for each house. For each `Id` in the test set, you must predict the value of the `SalePrice` variable. 

## Approach
The project follows a structured data science pipeline:

EDA -> Data Cleaning -> Feature Engineering -> Modelling

This is explained in more detail as it takes place within the notebook.

## Results
| Model | RMSE |
|---|---|
| Random Forest (baseline) | 0.1419 |
| XGBoost (untuned) | 0.1350 |
| XGBoost (tuned) | 0.1253 |
| Kaggle Leaderboard | 0.12958 |

My final submission placed in the top 43% as of time of submission.

## Technologies
- Python
- pandas
- numpy
- scikit-learn
- XGBoost
- matplotlib
- seaborn

## Usage
As per Kaggle's terms the dataset required is not included in the repository. To run the notebook locally you can download the dataset from the [competition page](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) and place the files in the working directory.

## Kaggle Notebook
My full notebook is also available on Kaggle [here](https://www.kaggle.com/code/callumbuchan/house-price-competition)
