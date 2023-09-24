# Price prediction case study
In this project, I develop a simple model to predict units sold for all products in a fictional Company's portfolio. 
- I begin by visualizing the data to understand its structure.
- I then proceed to engineer relevant features that might help in predicting the distribution of units sold for each product, given the product's price and product attributes.
- I plot correlations among the key variables.
- I establish criteria for evaluating a predictive model.
- I implement three different models:
    - A baseline model that predicts using the previous value of the target variable.
    - A simple linear model based only on the lag of the target variable, plus the log price.
    - A full linear model including most of the engineered features.
- I find that the full linear model performs best. I then visualize the best model's point estimates for all items across the portfolio, with a 95% empirical confidence interval.
- I discuss interpretation of the best model's fitted parameters.
- I compare the best model's estimated risk against the baseline model.
- I summarize and give suggestions for improvement.
