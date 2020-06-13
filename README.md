# Recommendation-Engine

# Introduction
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.

**1. Exploratory Data Analysis**

Before making recommendations of any kind, we need to explore the data we are working with for the project. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. The first part is related to exploratory data analysis of the data sets.

**2. Rank Based Recommendations**

To get started in building recommendations, we first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**3. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. 

**4. Content Based Recommendations (EXTRA - NOT REQUIRED)**


**5. Matrix Factorization**

Finally, we complete a machine learning approach to building recommendations. Using the user-item interactions, we build out a matrix decomposition. Using the decomposition, we get an idea of how well we can predict new articles to an individual might interact with (spoiler alert - it isn't great).

# Libraries

- Pandas
- Numpy
- Pickle
- Matplotlib
