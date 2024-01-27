# Image_recogntion_project

This project refet to train a model to identify pictures for rock-paper-scissors
Different models were examined like XGboost, RandomForest Support Vector Machines and Stacking Classifier.
Model were trained with cross validatiion techniques
Dataset was acuqired byKaggle which is accessible from the link : https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors
The trained model is playing against a virtual oppenent. Oppenent chooses a random image and flips it (horrizontaly or vertically) and add some noise.
Afterwards it is given as input to the model to identify and choose the optimal move to win the round.
It is assumed that our model is playing for 100 round starting with 10 monetary units.
Final our model was tested in a random image obtained from a google search.
