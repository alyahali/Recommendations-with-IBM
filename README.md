# Recommendations-with-IBM
# Project Motivation:
This project is part of Udacity Data Scientists Nano degree program.
## Introduction:
In this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they might like. 

# Project Files:
- Recommendations_with_IBM.ipynb - provides a complete walkthrough of the tasks as Jupyter Notebook
- Recommendations_with_IBM.html - provides a complete walkthrough of the tasks as html version Notebook
- data folder - contains two files:
    - articles_community.csv - contains article descriptions and details.
    - user-item-interactions.csv - contains the interaction details of users and articles.
    
# Project Tasks: 
1. **Exploratory Data Analysis** :
Before making recommendations of any kind, we will need to explore the data you are working with for the project. There are some basic, required questions to be answered about the data we are working with.
2. **Rank Based Recommendations** :  
To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most 
popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
3. **User-User Based Collaborative Filtering** : 
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 
4. **Matrix Factorization** :
Finally, we will develop a machine learning approach to building recommendations. 
Using the user-item interactions, we will build out a matrix decomposition. 
Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). 
We will finally discuss which methods we might use moving forward, and how we might test whether our recommendations are working for engaging users or not.

# Prerequisites:
Python versions 3.0+
pandas 0.23.4
numpy 1.15.4
Matplotlib


## Acknowledgements
I wish to thank [IBM Watson Studio](https://dataplatform.cloud.ibm.com/login) for dataset, thanks for [GitHub](https://github.com/) for examples, and thanks [Udacity](https://www.udacity.com/) for 
advice and review.
