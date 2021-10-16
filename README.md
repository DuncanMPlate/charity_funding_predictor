# charity_funding_predictor

## Overview 

The goal of this project was to use the data provided to accurately predict whether or not a funded charity would prove successful. 

## Results 


# Data Processing

* The target variables we determined were Classification and Application type.
* We dropped EIN and Name as they were identification columns and would only serve to bloat the data and clog the NN
* All other columns were features 

# Compiling, Training, and Evaulating the Model
After several iterations, the final model looked like this <img src='https://github.com/DuncanMPlate/charity_funding_predictor/blob/main/model.png?raw=true' height='150px'> 

I tweaked this model for many hours, changing both the data processing and the model shape on various occasions. I included detailed notes during this process within the main.ipynb file

## Summary

In the end I was unable to bring the model above an accuracy score of around 72.5%. This was largely disappointing and I had hoped for better but could not affect the necessary changes to do so. I personally feel like a Random Forest model would have a better time correctly predicting the outcomes of a funding campaign, as it would be able to make better use of the features of the dataset. 


