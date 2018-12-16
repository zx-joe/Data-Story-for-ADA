---
layout: post
title: Descriptive statistics
author: How the data looks like
---
To make a hit movie,various features are deserved for detailed analysis, both numerical and nonnumerical values. In this part, our aim is to get intuitive relations between Amazon rating and each potential feature.

### Relation between Amazon Rating and Genres
When making movies, in addition to simple numbers like budget and revenue, nonnumerical values are also informative, for example, the genres of movies. In typical years , specific genres of movie tend to lead a fashion, and greatly affect the review, rating and other forms of evaluations towards a film. As master students in area of science and technology, interesting science fiction movies will always attract us, but we won't have a chance to make a review on romance movie since computer is all we love. 

<iframe src="https://plot.ly/~zx_haowan/10/evoluation-of-genres-through-years/" width="100%" height="400px"></iframe>

Drama has always been a leading trend in history, followed by comedy, and little attention is paid to foreign movies. The trend of other genres have been fluctuating through time and markets of movies for that are usually changing. Intuitively, a genre will affect the rating and review length of a movie since a hot type will attract more people and arouse their thoughts for more review texts, so average rating and review length of each genre will be analyzed.
<iframe src="https://plot.ly/~zx_haowan/18/average-rating-and-average-length-of-review-in-all-genres/" width="100%" height="400px"></iframe>
Most genres share the close average ratings and Science Fiction movies are rated highest. However, Visually there is no direct relation between average rating and review length among different genres, at least no linear relation. Well, it's a little tricky, but we will focus on review later.
Intuitively, what are the evaluations other than ratings that can affect the quality of a movie? Yes, revenue, popularity and audience vote! So what's the relation between genres and these values?
<iframe src="https://plot.ly/~zx_haowan/16/popularity-revenue-and-average-for-all-genres/" width="100%" height="400px"></iframe>
Now we do have a clearer view of what kind of movie can bring profit or reputation. But what's the interconnection? Again, it's tricky to answer, since a mere genre number of 20 is not sufficient for numerical-level analysis.


### Relation between Amazon Rating and Directors
Director is also an important factor that lead to profit and review. Personally, if James Cameron directs a new movie, I will definitely go to the cinema for it and make my reviews after the payment. It's called the influence of celebrity. Compared with other crew or cast in movie production, a director is perhaps the most important role in a movie, and we will analyze that. In case of randomness, we get the average ratings for all views of 20 directors that direct most movies.
<iframe src="https://plot.ly/~zx_haowan/12/average-rating-for-top-20-popular-directors/" width="100%" height="400px"></iframe>
Since these 20 directors participate in more movies than others, they have their own charms. All of them get a rating over 3.0 and most of them have a rating over 4.0, which can show their ability of directing movies to some degree, making them popular when making a movie. 
<iframe src="https://plot.ly/~zx_haowan/14/average-vote-and-profit-for-top-10-popular-directors/" width="100%" height="400px"></iframe>
Those directors are popular for other reasons, maybe they do not always make a movie that has a good reputation shown by vote, but they can bring the movie producers profits with great probability. The average profit proportion of these popular directors are all greater than 0, some even reach the profit proportion of 5! From the point of movie producers, they care about relationship between revenue and budget most, which can be shown by the feature value of profit. Thus, making an invitation to popular directors lead to a shorter path for making profit.

### Relation between Amazon Rating and Production Companies
Production companies of movies also lead to an intuitive thought, since they consist of a whole group of crew. Maybe some of them are not as famous as a hot director, their stable cooperation inside a mutual company will definitely affect the quality of a movie. Again, we focus on the distribution in top 10 productive companies to avoid randomness.

<iframe src="https://plot.ly/~zx_haowan/1/money-in-budget-or-revenue-vs-companies/" width="100%" height="400px"></iframe>
Large companies always lead to high revenue and high budget-to-revenue ratio as well. The top movie-maker company Warner Bros. lead to the highest average revenue, and making its role in the market of movie making. Also it seems that rating and vote have the same trend among these companies, since the shape of line plots are similar.

### Geographic Distribution of Movie Rating
From the point of geographic distribution, a movie can also be affected by where it's produced since different countries have different national economic conditions and lead to different average ratings of the movies.
<iframe src="map/Overall_Ratings_with_Heatmap.html" width="100%" height="400px"></iframe>
Most areas have an average rating of about 3.5, and the average is especially higher in Europe, east Asia, north Africa, North America and India through the global map. But what are the specific strengths in each country? In other words, different kind of genres may conform to different distributions. For example, if we wish to watch animations, obviously Japanese animations are a great choice, but it will be too biased since lots of European countries pay little attention to animations. So let's focus on comedy, an eternal component in the movie industry.
<iframe src="map/Comedy_Ratings_with_Heatmap.html" width="100%" height="400px"></iframe>
Most countries have the similar average rating with all movies, and it can be understood that these countries develop comedy movies with at least average efforts. However,colors become obviously lighter in China, Russia and South America, these areas are not good at making people laugh compared with other countries.

### Relation between Amazon Rating and TMDB Vote

In the two datasets(Amazon and TMDB), we have two different ratings for a certain movie. One is from Amazon reviewers, which is a rating from 1 to 5 given on the movie products from Amazon. The other is from TMDB users, who usually should be movie fans who give a rating from 1 to 10 to the movies. What is the relation between these two ratings? We compared the two average ratings on each movie and made a scatter plot:

![tmdb-amazon](img/descriptive/tmdb-amazon.png)

We saw a moderate positive correlation between the two ratings. This means the ratings on the two platforms are overall consistent.

### Relation between Amazon Rating and Movie Budget/Revenue

We are also interested in how budget and revenue of a movie correlates with its rating. Does high budget always lead to a blockbuster? We made a scatter plot for these three factors:

![budget-revenue-rating](img/descriptive/budget-revenue-rating.png)

Do high budgets correlates with high ratings? No. There is a very weak negative correlation between budget and rating, so spending a lot of money doesn't always makes a high-rating movie.

Do high revenues correlates with high ratings? Not really. The positive correlation is rather weak. So we can't tell if a highest grossing movie can get good reputation.

And how about the relation between budgets and revenues? We noticed a moderate positive correlation between these two factors. Maybe movies are a kind of investment where you are able to get high returns with high budgets.