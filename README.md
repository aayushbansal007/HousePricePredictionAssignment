# HousePricePredictionAssignment
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia

## Table of Contents
* [Business Understanding](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Business Understanding
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

 

Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusions
<p>Although the Ridge Regression model performed better in terms of R2 values for train and test,
it is better to use Lasso because it fetches and assigns a null value to non-essential features, allowing us to select
predictive variables.
    
It is always advisable to use a simple but robust model.</p>

<h3>Which variables are significant in predicting the price of a house,</h3>

<p>The variables listed below are significant in price prediction:</p>
<ul>
    <li>LotArea (Lot size in square feet)</li>
    <li>OverallQual (Rates the overall material and finish of the house)</li>
    <li>OverallCond (Rates the overall condition of the house)</li>
    <li>YearBuilt (Original construction date)</li>
    <li>BsmtFinSF1 (Type 1 finished square feet)</li>
    <li>TotalBsmtSF (Total square feet of basement area)</li>
    <li>GrLivArea (Above grade (ground) living area square feet)</li>
    <li>TotRmsAbvGrd (Total rooms above grade (does not include bathrooms))</li>
    <li>Street_Pave (Pave road access to property)</li>
</ul>
<h3>How well those variables describe the price of a house.</h3>

<table style="width:500px;text-align:center;font-size:20px;">
    <tr>
        <th>Metric</th>
        <th>Ridge</th>
        <th>Lasso</th>
    </tr>
    <tr>
        <td>R2 Score train</td>
        <td> 0.8811</td>
        <td> 0.8818</td>
    </tr>
    <tr>
        <td>R2 Score test</td>
        <td> 0.8705</td>
        <td> 0.8711</td>
    </tr>
</table>

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Technologies Used
- Python 3.9

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@aayushbansal007] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->