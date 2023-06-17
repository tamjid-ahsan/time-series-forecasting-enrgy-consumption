# time-series-forecasting-enrgy-consumption
WIP, Analysis details will come soon, after done with analysis and ML. `notebook.ipynb` contains WIP code.

# About Dataset:

PJM Hourly Energy Consumption Data BY **Rob Mulla**. [Source](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)

PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.

The hourly power consumption data comes from PJM's website and are in megawatts (MW).

The regions have changed over the years so data may only appear for certain dates per region.
 
# Next Steps
- try out different models
    - Prophet | NeuralProphet [*](https://www.kaggle.com/code/antonmurashko/time-series-forecasting-with-prophet-yt) [1](https://bobrupakroy.medium.com/yes-our-favorite-fbprophet-is-back-with-multivariate-forecasting-785fbe412731) [2](https://www.microprediction.com/blog/prophet)
    - ANN: LSTM
    - ARIMA models; and its extensions like SARIMA, SARIMAX
    - scikit-learn based NN
    - LightGBM
    - AutoARIMA
    - Tsfresh | Darts | Kats [1](https://www.analyticsvidhya.com/blog/2022/05/5-python-libraries-for-time-series-analysis/) [2](https://towardsdatascience.com/3-unique-python-packages-for-time-series-forecasting-2926a09aaf5b)
- More robust cross validation for models
- Add more features (weather forecast data, holidays, major events, season)

# Disclaimer
This project is heavily influenced by [`ROB MULLA`](https://www.kaggle.com/code/robikscube/time-series-forecasting-with-machine-learning-yt). [[YouTube - p1](https://www.youtube.com/watch?v=vV12dGe_Fho), [Youtube - p2](https://www.youtube.com/watch?v=z3ZnOW-S550) as of June 17, 2023.]

___
contact: <a href="mailto:tamz888@yahoo.com">tamz888@yahoo.com</a> [<img src="https://raw.githubusercontent.com/tamjid-ahsan/ml-endpoint-docker-gunicorn-flask/main/data/TAlogo1.png" alt="TA" height="3%" width="3%">](http://linkedin.com/in/tamjidahsan/)
___