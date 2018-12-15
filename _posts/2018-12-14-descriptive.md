---
layout: post
title: Descriptive statistics
author: How the data looks like
---

First, we've done some simple descriptive statistical analysis on the two datasets.

### Relation between Amazon rating and TMDB rating

In the two datasets(Amazon and TMDB), we have two different ratings for a certain movie. One is from Amazon reviewers, which is a rating from 1 to 5 given on the movie products from Amazon. The other is from TMDB users, who usually should be movie fans who give a rating from 1 to 10 to the movies. What is the relation between these two ratings? We compared the two average ratings on each movie and made a scatter plot:

![tmdb-amazon](img/descriptive/tmdb-amazon.png)

We saw a moderate positive correlation between the two ratings. This means the ratings on the two platforms are overall consistent.

### Relation between Amazon rating and movie budget/revenue

We are also interested in how budget and revenue of a movie correlates with its rating. Does high budget always lead to a blockbuster? We made a scatter plot for these three factors:

![budget-revenue-rating](img/descriptive/budget-revenue-rating.png)

Do high budgets correlates with high ratings? No. There is a very weak negative correlation between budget and rating, so spending a lot of money doesn't always makes a high-rating movie.

Do high revenues correlates with high ratings? Not really. The positive correlation is rather weak. So we can't tell if a highest grossing movie can get good reputation.

And how about the relation between budgets and revenues? We noticed a moderate positive correlation between these two factors. Maybe movies are a kind of investment where you are able to get high returns with high budgets.
