# SC1015 Mini Project

## Problem Statement: 
Analysing Used Car Sales Data to understand what attributes affect the Selling Price of Used Cars most strongly.
(1) We aim to construct a neural network to predict the prices of Used Cars  
(2) We will propose which attributes should be considered by a prospective seller looking to list their car for sale. This will assist sellers with setting a reasonable price for their car and improve likelihood of successful sales, maximising profit earned from the sale where possible 
(3) We could analyse the most value for money option depending on the mileage, type of car and sale price of the car 

## Dataset Used: https://www.kaggle.com/datasets/sandeep1080/used-car-sales/data

## Members
Name: Kee Chong Wei |  Matriculation Number: U2320846D 
Name: Jiang Zong Zhe | Matriculation Number: U2322460F 
Name: Chew Jin Cheng | Matriculation Number: U2321537J

#### Marking Criteria
| Criteria      | Description |
| ----------- | ----------- |
| :memo: 10% for coming up with your own problem definition based on a dataset      | Based on the nature of the dataset, we brainstormed and decided to angle our analysis toward helping car owners calculate a reasonable price to sell their cars depending on certain attributes of their car |
| :memo: 10% for data preparation and cleaning to suit the problem of your choice   | We exhibited this in multiple ways <ul> <li> We searched for null values and removed them where necessary. </li> <li> We searched for outlier values and removed them where necessary </li> <li> We normalised data for input into our Bilayer Perceptron as it requires its inputs to be within similar scale and magnitude to prevent overrepresentation </li> <li> We performed One-Hot Encoding on Categorical Variables before feeding them into our Random Forest Models </li> </ul>|
| :memo: 20% for exploratory data analysis/visualization to gather relevant insights | We demonstrated this through <ul> <li> Plotting box-and-whisker plots to visualise distribution of data with respect to specific variables </li> <li> Plotting a KDE Plot and Scatter Plot to further analyse a correlation we were dubious of </li> <li> We plotted a correlation matrix with a heatmap to better visualise the correlation coefficients of numerical variables with Sold Price </li> </ul>|
| :memo: 20% for the use of machine learning techniques to solve specific problem | We utilised <ul> <li> We utilised a Linear Regression Model to predict Sold Price of a car depending on the retail price of the car, price the seller bought the car for and Engine Power of the car </li> <li> We utilised a Random Forest Model to predict Sold Price based on Car Type and Energy (car fuel) </li> </ul>|
| :memo: 20% for the presentation of data-driven insights and the recommendations ||
| :memo: 10% for the quality of your final team presentation and overall impressions ||
| :memo: 10% for learning something new and doing something beyond this course | We tried our hand at implementing a Bilayer Perceptron using Engine Power as the Input Variable| 