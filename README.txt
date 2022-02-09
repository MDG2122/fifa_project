My first personal project, predicting FIFA ratings using sofifa and transfermarkt databases. 
Originally wanted to feed the model with a 3d matrix, where the 3rd dimension represents the seasons (17-18,18-19 an so on), but it was not possible because of insufficient data. 
The model consist on a standard Neural Network and is fed with data from a specific season (ex: 17_18).
Data needs to be downloaded and read by load.csv (sofifa) and load.excel (transfermarkt)
Predictions are only approximations (mse = 5.02), to increase the performance, more data is necessary.
This project is only a prototype, it can still be further improved and tweaked.  
The model has bigger error when ovr of the player is less than 70.
The ideal model should also predict potential, and attributes from the player (or even work rate, weak foot, etc), but more data is needed to feed the Neural Network for that to happen.
