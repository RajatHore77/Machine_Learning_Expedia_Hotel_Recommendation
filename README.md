# Machine_Learning_Repository
Project Description: Expedia has provided logs of customer behavior. 
These include what customers searched for, how they interacted with search results (click/book), whether or not the search result was a travel package. The data is a random selection from Expedia and is not representative of the overall statistics. We need to predict which hotel group a user is going to book. Expedia has in-house algorithms to form hotel clusters, where similar hotels for a search (based on historical price, customer star ratings, geographical locations relative to city center etc.) are grouped together. These hotel clusters serve as good identifiers to which types of hotels people are going to book, while avoiding outliers such as new hotels that don't have historical data. My goal is to predict the booking outcome (hotel cluster) for a user event, based on their search and other attributes associated with that user event.

Strategy to solve the problem:

The tasks involved are the following:

1.Download and loading the Train, Test and Destination dataset. 2.Analysis of Train dataset based on hotel search by a user (Do statistical analysis of the data). 3.Cleaning and preprocessing of datasets. 4.Split the data into train and test dataset. 5.Featuring the data to make it ready to execute in the machine learning algorithm.

6.Since I do not have any idea the values for the output data might be, making it impossible for you to train the algorithm the way you normally would. So this is definitely an unsupervised machine learning problem.so I am going to run different machine learning model on this data set and found the best model in terms accuracy score.

7.If machine learning model does not give satisfactory accuracy then I will switch some different model in which this data will fits well and give me more accurate result.

8.I will store the top 5 predicted clusters for each user based on their search destination in a CSV file which will be my final result submission file.

We need to install the below library in python library repository

Install pretty table - Command:sudo pip3 install PTable
