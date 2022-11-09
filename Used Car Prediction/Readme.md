# Used Car Price Prediction

The data is import from https://raw.githubusercontent.com/aravind9722/datasets-for-ML-projects/main/cardekho_dataset.csv

#### Life cycle of Machine learning Project 

* Understanding the Problem Statement
* Data Collection
* Exploratory data analysis
* Data Cleaning
* Data Pre-Processing
* Model Training 
* Choose best model

## 1) Problem statement.

* This dataset comprises used cars sold on cardehko.com in India as well as important features of these cars.
* If user can predict the price of the car based on input features.
* Prediction results can be used to give new seller the price suggestion based on market condition.

## 2) Data Collection.
* The Dataset is collected from scrapping from cardheko webiste
* The data consists of 13 column and 15411 rows.

## Feature Information
* **car_name:** Car's Full name, which includes brand and specific model name.
* **brand:** Brand Name of the particular car.
* **model:** Exact model name of the car of a particular brand.
* **seller_type:** Which Type of seller is selling the used car
* **fuel_type:** Fuel used in the used car, which was put up on sale.
* **transmission_type:** Transmission used in the used car, which was put on sale.
* **vehicle_age:** The count of years since car was bought.
* **mileage:** It is the number of kilometer the car runs per litre.
* **engine:** It is the engine capacity in cc(cubic centimeters)
* **max_power:** Max power it produces in BHP.
* **seats:** Total number of seats in car.
* **selling_price:** The sale price which was put up on website.


## Task we have performed :
- Import data from the link and required libraries
- Separate numerical and Categorical Fetures
- Univariate Analysis
- Multivariate Analysis
- Check Multicollinearity for Categorical Features
- Checking Null value
- Graphical Visualisation
    - Kilometer driven vs Selling Price
    - Fuel Type vs Selling Price
    - Most sold Fuel type
    - Fuel types available and mileage given
    - Mileage vs Selling Price
    - Vehicle age vs Selling Price
    - Vehicle age vs Mileage
    - Transmission Type
- Question from this dataset
  - Most sold cars in used car websites
  - Most selling brand
  - Most costlier Brand and Costliest Car
  - Most Mileage Brand and Car Name
  - Car with Highest Mileage


## Final Report
* The datatypes and Column names were right and there was 15411 rows and 13 columns
* The `selling_price` column is the target to predict. i.e Regression Problem.
* There are outliers in the `km_driven`, `enginer`, `selling_price`, and `max power`.
* Dealers are the highest sellers of the used cars.
* Skewness is found in few of the columns will check it after handling outliers.
* Vehicle age has negative impact on the price.
* Manual cars are mostly sold and automatic has higher selling average than manual cars.
* Petrol is the most preffered choice of fuel in used car website, followed by diesel and LPG.
* We just need less data cleaning for this dataset.

















