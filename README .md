# Housing Price Prediction
> Problem : A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company wants to know:
Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.
Project : This project is about identifying the best features which can let company know that on the basis of which variables it can help company 
increase the resale of house in new market. There are multiple factors which identifies this. As part of concept Lasso and Ridge techniques have been used to identify the most impportant variables and to build model.Looking at some parameters like R2 value, root mean square error it will be identofied which model is best and going forward same will be used for prediction.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?

> Problem : A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company wants to know:
Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.
Project : This project is about identifying the best features which can let company know that on the basis of which variables it can help company 
increase the resale of house in new market. There are multiple factors which identifies this. As part of concept Lasso and Ridge techniques have been used to identify the most impportant variables and to build model.Looking at some parameters like R2 value, root mean square error it will be identofied which model is best and going forward same will be used for prediction.

- What is the business probem that your project is trying to solve?

Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.

- What is the dataset that is being used?

Previous years dataset about the house selling pattern on the basis of house condition, locality , features etc. have been used.


## Conclusions

Best Alpha value in case of Ridge and Lasso analysis is as below:
Ridge - 0.6
Lasso - 0.0001
The Mean Squared error in case of Ridge and Lasso are:
Ridge - 0.01415
Lasso - 0.01411
The Mean Squared Error of Lasso is less then Ridge
Also, in case of Lasso some features get reduced ( due to some of coefficients of feature became 0), Lasso has a better performance over Ridge.
Hence based on Lasso, the factors that generally affect the price are:
1) MSZoning - Zoning classification
2) OverallQual: Rates the overall material and finish of the house
3) GrLivArea: Above grade (ground) living area square feet
4) Foundation: Type of foundation
5) TotalBsmtSF: Total square feet of basement area
6) GarageCars: Size of garage in car capacity
7) BsmtFinSF1: Type 1 finished square feet


## Technologies Used
- Python 3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by. Upgrade Ai/ML course
- References if any...
- This project was based on US-based housing company named Surprise Housing 


## Contact
Created by [@madhuomer0912] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->