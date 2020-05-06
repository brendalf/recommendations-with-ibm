# Recommendations with IBM
## Introduction
For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

<img src="https://video.udacity-data.com/topher/2018/September/5ba02d6d_screen-shot-2018-09-17-at-3.40.30-pm/screen-shot-2018-09-17-at-3.40.30-pm.png" />

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, I did a study of the data available on the IBM Watson Studio platform. You can create your own account to become a part of their community, and get a better understanding of their data <a href="https://dataplatform.cloud.ibm.com/" target="_blank">by creating an account on the platform here</a>.

## Recommendations Systems
**I. Rank Based Recommendations**  
To get started in building recommendations, I first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**II. User-User Based Collaborative Filtering**  
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

**III. Content Based Recommendations**  
Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

**IV. Matrix Factorization**  
Finally, I write a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.
