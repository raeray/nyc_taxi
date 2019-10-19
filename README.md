# nyc_taxi

## Project Description

The goal of our project is to estimate the price of New York Taxi fare. We are given a training data set of 55 million rows. We will create various models that attempt to estimate the target variable, and the metric we will use to evaluate the quality of our model will be the root mean square error:

\begin{equation*}
\sqrt{ \frac{1}{n} \sum_{i=1}^n \hat (y_i - y_i)^2 }
\end{equation*}

The project follows the framework provided by a Kaggle competition from Google Cloud (https://www.kaggle.com/c/new-york-city-taxi-fare-prediction).
