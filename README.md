# Harman's Portfolio
Harman Dhaliwal Data Science Portfolio

# [Ball Image Classifier](https://github.com/harmandhaliwal/Ball-Image-Classifier)
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities.

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.

![](/images/matrix_results.png)

# [Movie Similarity](https://github.com/harmandhaliwal/MovieSimilarity) 
In this Project, I used NLP to find the degree of similarity between movies based on their plots available on IMDb and Wikipedia, then seperated them into groups, also known as clusters. Next, I created a dendrogram to represent how closely the movies are related to each other. The dataset I used contains the titles of the top 100 movies on [IMDb](https://www.imdb.com/) as well as each movie's plot summary from both IMDb and Wikipedia.

# [Song Genre Classification](https://github.com/harmandhaliwal/SongClassification)
Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based on track information derived from [Echonest](http://the.echonest.com). I began by using `pandas` and `seaborn` packages for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors(data cleaning & exploratory data visualization). Next, I used the `scikit-learn` package to predict whether you can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc, through simple machine learning algorithms such as decision trees and logistic regression.

# [Google Trends Time Series Analysis](https://github.com/harmandhaliwal/GoogleTrendsTimeSeriesAnalysis)
In this notebook I used a dataset that contains Google trend data for the keywords diet', 'gym' and 'finance' to see how they vary over time. I scraped this dataset using [Google Trends](https://trends.google.com/trends/?geo=US). Next, I wrangled/cleaned the data then I preformed exploratory data analysis. Seasonality, trends, correlation, autocorrelation, and first order differencing were concepts that we looked at during the analysis.

# [NBA Salary Predictor](https://github.com/harmandhaliwal/NBA_Salary_Predictor)
* Created a tool that estimates NBA player annual salary (MAE ~ $ 484K) to help NBA free agents/front offices negotiate future contracts.
* Scraped NBA player contract data and NBA player per game stats data from [Basketball Reference](https://www.basketball-reference.com/)
* Preformed data cleaning/wrangling on raw scraped dataset.
* Conducted exploratory analysis to view and analyze correlation plot/regression line scatter plot
* Engineered features from the per game stats dataset to quantify the value teams put on particular stat categories. 
* Built models using linear and multiple linear regression.

