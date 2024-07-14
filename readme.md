
![hs](https://github.com/user-attachments/assets/fed54009-3979-44b0-a8a7-4c953624f672)

# King County House Sales Price Prediction
## Project Overview
This project focuses on predicting house prices in King County, Washington, using regression modeling. The goal is to provide real estate agents with accurate pricing recommendations for homeowners looking to sell their properties as well as homebuyers looking to get a fair deal. By setting the right price, agents can attract more buyers and ensure a quicker sale.

### Stakeholder
Real Estate Agents: The primary stakeholders who will benefit from accurate pricing recommendations to help homeowners sell their houses quickly and at competitive prices.

### Objective
To develop a regression model that predicts the sale price of homes based on various features such as square footage, number of bedrooms, bathrooms, location, and other relevant variables.

## Approach
### Model Development: Use regression model to predict the sale price of homes.
Feature Analysis: Identify which features are the most influential in determining the price.
Prediction Accuracy: Evaluate model performance using metrics like Root Mean Squared Error (RMSE) and R².
## Dataset
The project uses the King County House Sales dataset, kc_house_data.csv, which contains the following features:

## Column Names and descriptions for Kings County Data Set
* **id** - unique identified for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors


## Project Steps
### Data Collection and Preparation

Loading and cleaning the dataset.
Handling missing values and outliers.
Converting dates and categorical variables to appropriate formats.

## Exploratory Data Analysis (EDA)

Visualizing the distribution of the target variable (price).
Analyzing relationships between price and key features (e.g., sqft_living, bedrooms, bathrooms).


## Model Development

linear regression model.
Switching correlated variables to check the variables yielding best model performance.
Evaluating model performance.

## Business Insights

Provide actionable recommendations to real estate agents on pricing strategies.
Highlight which home features add the most value to the property.


## Deliverables
GitHub Repository: .
Jupyter Notebook: .
Non-technical Presentation: Summarizes the project, key findings, and actionable insights for stakeholders.


# Conclusion
>>>>>>> 478a38f01065ffa1c092edbcd15b2e36380f26f3
