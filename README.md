# Recommendations-with-IBM

## Introduction

For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations using different methods.

The project is divided into the following tasks

#### I. Exploratory Data Analysis
Here I explored the dataset provided for the project to gain a better understanding about the data and answer some required questions within the notebook.

#### II. Rank Based Recommendations
Since there are no current metrics to know if a user likes an article from the dataset provided, the number of user interactions with articles was used to determine the popularity of an article  

#### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, a function was made to get similar users in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

#### IV. Matrix Factorization

Use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform

## File Descriptions
The files in this repository are listed below:
* `articles_community.csv`: CSV file containing detailed information about articles.
* `user-item-interactions.csv`: CSV file containing user-article interactions.

* `Recommendations_with_IBM.ipynb`: Python notebook for Exploring the project data and building recommendation.  
* `project_tests.py`: Test file for results
## Licensing

This project was done as part of the [Udacity Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
