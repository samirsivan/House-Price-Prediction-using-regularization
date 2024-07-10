# House Price Predicting Assignment
 A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. A regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not is needed.

 
## General Information to find
- The company is looking at prospective properties to buy to enter the market.
- A regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not is needed.
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- The optimal value of lambda for ridge and lasso regression is als needed.
- This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test,
it is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose
the predictive variables.
It is always advisable to use simple yet robust model.
Equation can be formulated using the features and coefficients obtained by Lasso



