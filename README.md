# Kaggle_Titanic
Python code to predict Titanic survivors in Kaggle competition. Train.csv contains about 1000 training examples
and Test.csv contains about 400 passengers whose fate has to be predicted.

Important features are sex (woven more likely to survive), age (kinds more likely to survive), family size, and social status (represented by ticket price but also othe features).

One of the main challenges is that the age is missing for several passengers.  

This is a first Python code I wrote to participate to the the Titanic Kaggle competition

I have tested some other algorithms but I used the SVM algorithm as implemented in the
Scikit-learn libraries.

The script performs quite well with a score of 0.81818 and a position on the top 3% of the kaggle leaderboard.

However, the algorithm strongly overfits the training data due to the huge number of ``Ticket''
