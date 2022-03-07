My first personal project, predicting FIFA ratings using sofifa and transfermarkt databases. 
Originally wanted to feed the model with a 3d matrix, where the 3rd dimension represents the seasons (17-18,18-19 an so on), and use a RNN (LSTM) for the model, but it was not possible because of insufficient data. 
The model consists of a standard Neural Network and is fed with data from a specific season (ex: 17-18).
Data needs to be downloaded and read by load.csv (sofifa) and load.excel (transfermarkt). Direction where the data is stored needs to be indicated before reading it.
Transfermarkt databases were transformed from csv to xlsx (saved as excel books)
Predictions are only approximations (mse = 5.08), to increase the performance, more data is necessary.
This project is only a prototype, it can still be further improved and tweaked.  
The model has bigger error when the Overall of the player is less than 70. A separation of divisions or a league ranking column may improve this type of predictions.
The ideal model should also predict potential, and attributes from the player (or even work rate, weak foot, etc), but more data is needed to feed the Neural Network for that to happen.
It is important to mention that FIFA ratings are assigned based on people's opinions (real scouts, according to the company), so they are not necessarily perfect. Because of this, the disparity between my model values and real Ratings should not be considered strictly as an "error". To evaluate if my ratings are "correct" or "wrong" it would be necessary to know the opinion of a group of people about them. At the end, you want to satisfy the players of the game.

To see the code, open the last version of my project, named: "Fifa_deep_learning_Final_version.ipynb"

#Thank you for seeing my code!
#Made using: Google Colab
#Project made by: Massimo Di Gennaro
