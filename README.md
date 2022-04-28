# Prediction of Rank of a Football Team in a Season Based on Machine Learning and Statistics
A Python Notebook to perform Data Analysis and Prediction using a Football Dataset for the top 6 European Domestic Leagues. The notebook analyzes, preprocesses, constructs a Random Forest Regression Model and predicts the position at which the teams would finish at the end of the season.
The model is trained using data acquired from Kaggle (https://www.kaggle.com/datasets/slehkyi/extended-football-stats-for-european-leagues-xg)

# Table of Contents
* [Installation](https://github.com/sumitkhopkar25/football-team-rank-predictor/tree/main#installation)
* [Usage](https://github.com/sumitkhopkar25/football-team-rank-predictor/tree/main#usage)
* [Development](https://github.com/sumitkhopkar25/football-team-rank-predictor/tree/main#development)
* [Example of Prediction](https://github.com/sumitkhopkar25/football-team-rank-predictor/tree/main#example-of-prediction)
* [Acknowledgments](https://github.com/sumitkhopkar25/football-team-rank-predictor/tree/main#acknowledgments)

# Installation
Requires Jupyter Notebook to run the .ipynb file and basic Data Science libraries. 

Pandas installation - https://pandas.pydata.org/docs/getting_started/install.html <br>
Numpy installation - https://numpy.org/install/ <br>
Sklearn installation - https://scikit-learn.org/stable/install.html

Optional libraries to visualize the data - seaborn and matplotlib

Seaborn installation - https://seaborn.pydata.org/installing.html <br>
Matplotlib installation - https://www.tutorialspoint.com/how-to-install-matplotlib-in-python

# Usage
As you progress through the notebook, change the links to set them to your local file paths. The prediction is performed on teams from LaLiga for the year 2014 initially to check for the testing accuracy. After that prediction can be performed manually as per requirement by changing the variables for "football_test_data" and "league".

# Development
If you wish to check the result using different Machine Learning algorithms then you can do so by adding more models in the "Machine Learning Part" section markdown. Encoding and train-test split has already been done and you can change them as well. The ranking of the teams has been handled by the code and does not need any update because of model changes.

# Example of Prediction
![image](https://user-images.githubusercontent.com/63579785/165787505-be43b0ae-7cda-4fda-9922-dfac77a67d3e.png)

# Acknowledgments
Pradnyesh Bhalange
