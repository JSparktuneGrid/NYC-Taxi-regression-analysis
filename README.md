# NYC-Taxi-regression-analysis

## Issues
To predict taxi cab fares for The New York City Taxi & Limousine Commission, then created the deliverable for the original ask from their client: a regression model.

## Response
A multiple linear regression (MLR) model was chose to create, based on the type and distribution of data provided. The MLR model showed a successful model that estimates taxi cab fares prior to the ride.
The model performance is high on both training and test sets, suggesting that the model is not over-biased and that the model is not overfit. The model performed better on the test data.

### Model metrics:
Net model tuning resulted in:
- R^2 0.81, meaning that 81.5% of the variance is described by the model.
- MAE: 2.4
- MSE: 19.1
- RMSE: 4.4

## KEY INSIGHTS
1. The feature with the greatest effect on fare amount was ride duration, which was not unexpected. The model revealed a mean increase of $9.6 for each additional minute, however, this is not a reliable benchmark due to high correlation between some features.
2. Request additional data from under-represented itineraries.
3. The New York City Taxi and Limousine commission can use these findings to create an app that allows users (TLC riders) to see the estimated fare before their ride begins.
4. The model provides a generally strong and reliable fare prediction that can be used in downstream modeling efforts.

## Build a multiple linear regression model

**The purpose** of this project is to demostrate knowledge of EDA and a multiple linear regression model.

**The goal** is to build a multiple linear regression model and evaluate the model.

## Methodology
### PACE Method
**Part [01] : Plan and Analyze**
  - EDA & Checking Model Assumptions

**Part [02] : Construct**
  - Model Building and evaluation

**Part [03] : Excecute**
  - Interpreting Model Results
