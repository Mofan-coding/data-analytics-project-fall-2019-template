# Decisions Analytics Project Title
I made an exploratory data analysis on IMDb’s movie database using data analysis tool: R and Excel.I want to get a better understanding  about the movie industry development and try to analyze the influencing factors of movies revenue and Rating from the aspect of genres, runtime, production company and actors,

# Industry Question
These are the questions that I want to investigate

1. What kind of category of movies get higher revenue and rating?
2. If there's some connection between the length of movies and rating score?
3. What's the performance of the giant movie production company and the top 10 actors in the world?

# Decisions Analytics Project Title
1. How to know if its the right time to enter into movie industry? 
2. if you expect great returns from investing movies, how to choose the most suitable ones? 


# Industry
 1. Industry question: What's the develpment trend of movies? What's the connection between total revenue and rating score, genres? 
 2. Why improtant? Movies have become an important form of entertainment in our lives. How can we tell the greatness of a movie before it is released in cinema? 
 3. Further reading if interests:
 1) Movie Review Aggregator Ratings Have No Relationship with Box Office Success
 https://minimaxir.com/2016/01/movie-revenue-ratings/
 2)Data Science: Analysis of Movies released in the cinema between 2000 and 2017
 https://medium.com/datadriveninvestor/data-science-analysis-of-movies-released-in-the-cinema-between-2000-and-2017-b2d9e515d032
 

# Data Questions
 1. What kind of data was important to use to answer this question, how did you find it, and why did you use this information? Was there some data that you wish you had? If so, how would you change your approach?
 
 I need to find a large dataset of movies contains release year, genre, total revenue, runtime, IMDB rating, production company, director name, starring name and budget. I find a perfect dateset from kaggle. It provides enough information so that I can do the exploratory analysis.
 
 2. What metrics did you think were important to understanding a quantitative answer to your original question and why? Did you “translate” any of your data into numbers?
 
 The total revenue, IMDB rating score are used as the evaluation variable of the movie quality. And genre, runtime, production company and starring actor and budget can be seen as the factor of the total revenue and IMDB rating. These varibles are important because I try to figure about the connection between them.
 
 3.  Did you base your data analysis on another type of analysis or desired outcome?
 
 I also derive some insights from some movie industry analysis report.
 
 4. Use website links to your data sources
 
[IMDB dataset from kaggle] https://www.kaggle.com/orgesleka/imdbmovies

# Data Answers
 1. What were the results of your data analysis and how did this contribute to your final solution?
 
 The trend analysis show that the film market has increased rapidly in the past 30 years. And when we study the annual gross profit of movies, the income is very high and stable. Even though the number of movies has seen several fluctuation in the past twenty years. It tells us that it's the right time to enter into movie industry and high returns can be expected.
 
 The group comparative analysis shows that action movies can get the highest revenue and dramas tend to get higher rating score. And the most profitable movies come from series movies which have a large number of fans.
 
 I also learn that as for the giant movie production, Disney Picture's movies get the highest rating score and Paramount Picture does well in producing high revenue movies.As for the performance of top 10 actors,As for the giant movie production, Disney Picture's movies get the highest rating score and Paramount Picture does well in producing high revenue movies.
 As for the performance of top 10 actors, Jonny Depp is the champion for starring the most profitable movies and Leonardo wins when comparing the quality of movies.

From these results, I know that if I exptect great returns from investing movie, I will choose action movies and add some drama elements. I will find a fan movie and invite Depp as the starring actor.
 
 
 
 2. What type of visualizations can best demonstrate what you found and what you think is important to emphasize to your audience?
 
 Wordcloud， bar chart ，scatter plot can show the results comparative analysis clearly. And line chart is a good way to show the trend analysis.
 I think the "winner" in each comparative analysis should be emphasized to audience.
 
 
 3. Keep your data visualizations and tables in here for people to follow along with your analysis and explore how your data findings are relevant. 
 
![Alt text](https://github.com/jhu-decision-analytics/data-analytics-project-fall-2019-template/blob/master/bpd_overtime_count.png)

# Industry/Civic/Academic Answer(s)
 1. What’s the answer to your original question? Were you able to come to any type of conclusive answer—why or why not?
 
 1) What kind of category of movies get higher revenue and rating?
 Action movies are more easy to get higher revenue and the average rating for drama is the highest. Also, the serives movies always get the most revenue.
 I can come to this conclusive answer from conducting the group comparative analysis( the result is showed above).
 2) If there's some connection between the length of movies and rating score?
 I can't come to a conclusive answer because from the result ( showed above), I cannot tell if there's some connection between runtime and rating. Short-time movie and long-time movie are have the opportunity to get high rating score.
 3)What's the performance of the giant movie production company and the top 10 actors in the world?
 As for the giant movie production, Disney Picture's movies get the highest rating score and Paramount Picture does well in producing high revenue movies.
 As for the performance of top 10 actors, Jonny Depp is the champion for starring the most profitable movies and Leonardo wins when comparing the quality of movies.
 I can come to this conclusive answer from the group comparative analysis.
 

 
 -2. How would you build on your analysis if given more time?
 
 I would also conduct a regression analyis to find the most infulencial factor for the total revenue and IMDB score.
 I would built a text-analysis to analyze the comments on the IMDB. What's the most frequent words in the comments for a high-rating movie and for a low-rating movie？
 
 -3.  What do these answers mean for us in the real world?
 
 We can better choose a movie to watch.
 
 
 - 4. What do these answers mean for the audience in this industry?
 It's will contribute to the investment company to expect great returns in choosing which movie to invest.

