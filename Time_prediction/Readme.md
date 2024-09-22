To attract more drivers during peak load periods, I need to predict the number of taxi orders for the next hour.
To do this, I build a regression model and train it on historical order data.

Requirement: the RMSE metric on the test sample should be no more than 48.

Execution order:
- loading data and resampling by one hour,
- data analysis,
- training different models with different hyperparameters,
- testing on the test sample. 
