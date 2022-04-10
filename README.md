# macroseries

## Description:
Macroeconomic series forecasting: it is an R package that establishes a friendlier workflow and wraps time series functions for ARIMA and VAR models.
Furthermore, this packages **are** a friendlier wrap to time series functions.


## Aproach used in this package

Basically the approach I am using to "do" time series is to: 
  1. Establish training and test sets 
  2. Run a time series model on the training set
  3. Test in sample with Error Measures
  4. Check model assumptions
  5. Select the best model.
  6. Forecast it (single step or multistep)
  7. Test out of sample with Forecast Error Measures (FEM)
  8. Select the model that minimizes the FEM


The aim for this package is to make a simplify the workflow for time series forecasting. I hope it helps you!


## Special thanks to
I want to thanks Carlos Uribe for teaching me about time series models and letting me work with them for the viceministry. 
