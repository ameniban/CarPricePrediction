# CarPricePrediction
If you're looking to buy or sell a used car and have no idea of the approximate price, this project is for you. It helps you predict the price of a car by entering the car's name, company, year of manufacture and fuel type.
#First Step: Let's begin with downloading the dataset from Quikr.com : https://quikr.com
#Cleaning the raw data : steps were explained: 
##Year Column: 
- year has many unvalid values.
- Change the year column type from object to int
##Price Column:
- Remove 'Ask for price'
- Rmove the comma (objet-->int)
##Kms_driven:
- Remove "Kms"
- Missing Values
- Column type (objet-->int)
##Fuel_type:
- Missing Values.
##Name:
- Keep only the first three words.
#Machine Learning :Supervised Learning : the target is the 'Price' Column.
we chose to work with a Linear Regression model.
