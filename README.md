# Recommendations-with-IBM

## Installation 
This project requires Python 3.x and the following Python libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Jupyter-Notbook](https://jupyter.org/install.html)   
Or you could install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Project Introduction
For this project we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like.

## Project Description
This project is divided into the following tasks

1. Exploratory Data Analysis

Before making recommendations of any kind, we need to explore the data we are working with for the project. Dive in to see what we can find. 

2. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

4. Matrix Factorization

Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with.

## Run
In a terminal or command window, navigate to the top-level project directory finding_donors/ (that contains this README) and run the following command:

```
jupyter notebook Recommendations_with_IBM.ipynb

```

## Licensing
This project is licensed under the MIT License - see the LICENSE file for details

