# HR_Analytics_Linear-Regression
# Overview:

# Goal: 

The goal of the problem is to predict the annual compensation at which a participant gets placed after graduating 
from college.For each registration number in the test set,  you must predict a salary for the CTC variable.

# Metric to measure:

Your score is how much your predicted salary deviates from the actual salaries of the participants. This is simply known as accuracy.

# Problem Statement:

The provided dataset consists of information related to multiple participants from diverse backgrounds who graduated from institutes 
across India and have got placed at different roles in different firms.

# HR_Anlytics Using Supervised Learning

Python programing using Regression methods like Linear, KNN, LASSO and Decision Trees to predict CTC for a freshly graduated candidate 
from the University also tried boosting the model using Gradient Boosting/ Ada Boosting.

Intial Analysis : 

Found missing values in the dataset in the Recruitment Assessment data and Participant information data 
      - for the Participant information data, the 10 and 12 th marks have been replaced with Median since I found the board 
        name for those missing values of 12th and 10th.
      - for the Recruitment Assessment data - according to the data description document the "-1" values indicates that the person has
        not appeared for the test, it is considered as the missing data.

In case the score is -1 for this test, you could make use of the scores in the tests mentioned below to get more information. If the scores in the tests below are -1 as well, then it can be concluded that the candidate has not given a module listed here.
    

Dataset:
The problem consists of 3 separate datasets: Participant information, Recruitment Assessment data and Personality Test data. 
The Participant information has the profile information along with the placement information for every participant. 
The Recruitment Assessment data has score data for every participant who sits through the placement process. 
Similarly, the Personality test data has scores from a personality test conducted for all the participants.

You are expected to treat this as raw data and perform any necessary cleaning/validation steps as required.

Model Evaluation:
Each Model will get evaluated on the basis of RMSE. The model with the lowest RMSE will get ranked as the best model.  
