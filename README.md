# 10_RustyBargain_RegressionHyperparameterTuning

## About this Project

The hypothetical Rusty Bargain used car sales service is developing an app to attract new customers. In that app, customers can quickly find out the market value of their car. We have access to historical data: technical specifications, trim versions, and prices. We will build a model to predict the car value.

The project leverages grid pipelines to facilitate hyperparameter tuning of more advanced models. It also demonstrates how to evaluate models when the data scientist cares not only about model performance but also model training time. Model training is resource- and time-intensive, and tracking model training time is important for business interests.

## Running it Yourself

The Jupyter notebook is self-contained and reflects the outputs of the code contained within. If you would like to connect to your own environment and run the notebook, or make changes on your own fork of the repo, you may do so after cloning. Make sure the environment is either based in the upper-level folder to which you clone the repo, or be sure to replace the dataset file references with a direct local reference to the /datasets/ folder on your machine. 

The project relies on scikit-learn 1.5.1. Our lightgbm version is 4.5.0. The project is stable with Python 3.11.