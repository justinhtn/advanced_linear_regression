# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Surprise Housing wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We've identified for our modeling and feature selection techniques, our Ridge model is the most performant on training and test sets. This is contrary to intuition but it does look like our Lasso model did outperform Ridge on the training set. More work is needed to identify an adjustment, but we can see that our Ridge model does perform adequately against our test set. We also see that it performed better than our baseline linear regression model. Although test performance is not extremely high, it would aid any business in determining what price to re-sell a house for.

The most important features an analysis can use are below. I've included the coefficients so that an analysis can know to what extend these features are important compared to one another.

1. GrLivArea: 10094.828816
2. OverallQual: 9369.226077
3. 1stFlrSF: 7093.794628
4. TotalBsmtSF: 6357.671763
5. Neighborhood_NoRidge: 6019.516204


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@justinhtn] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
