# project_one

# Purpose of Analysis:

The purpose of this analysis is to see if we are able to predict the trends of the top 5 cryptocurrencies. We have 5 separate CSV files containing 5 years worth of performance data for Bitcoin; DogeCoin; Tether; Etherium; XRP. We created 5 separate DataFrames for each of the crypto currencies. The data for Etherium was used to test the initial machine learning model with the data sets that were available.

# Summary:

The model we used is the Random Forest Regressor Model since a classifier model would not be appropriate with the data we have, since we are actually predicted a numeric value. If we are able to get all the DataFrames on one DataFrame, we might want to consider using a classifier model to take in the data and predict which cryptocurrency the data is for.

# Results:

- The accuracy rate of 96% was achieved when trying to predict the closing value for Ethereum USD.
- The prediction by the machine learning model was 274.48, when the actual amount was 307.06.

# Topic

Our group chose to analzye 5 different cryptocurrencies with the goal of comparing their previous growth and tracking their trajectory in oder to see which would be the lucrative value to invest in. We chose to go with this topic because crypto is a modern market that many know about but not many have the information to understand its value. The question we hope to answer is to see which currency would be the best value for a customer. The 5 we choose were: Bitcoin, DogeCoin Tether, Etherium, and XRP.

# Github Management and Team Members - Roles

For this segment of the project Our communication as a group relies on using Slack.

- Nick is in charge of maintaining and organizing the github.
- Jacyntha is responsible for working on machine learning model.
- Saba is handling and retrieving the data, database and DataFrame.


# Database

Mongodb is used to store and manipulate data.
