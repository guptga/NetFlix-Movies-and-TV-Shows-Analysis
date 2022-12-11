# NetFlix Insights and Visualizations
 Netflix is one of the most popular digital streaming media service providers today. Netflix provides streaming services for movies and tv shows from various countries in the world. As a digital media with many users, Netflix also has a very large amount of data.This dataset consists of tv shows and movies available on Netflix as of 2020. In this jupyter notebook, I will perform data visualizations using Netflix data using matplotlib, seaborn and pandas. 
  
 ## Datasets
 The netflix dataset we have used is from kaggle, which is https://www.kaggle.com/code/aayushmishra1512/netflix-data-analysis-and-visualization/notebook
 For ratings we used OMdb api http://www.omdbapi.com/
 For csv data we used netfilx_titles.csv
 
## Data cleaning
 For data cleaning process 
 
 
 In this jupyter notebook we used netfilx_titles.csv, which contains movies and tv shows titles, show id, duration, years, ratings, directors, cast as columns we we are going to use further in the visualization in jupyter notebook using pandas library.
 First thing we have seen in this csv is that there are 476 null values in country column , so the first step was to fill these nulls values.
 Then we replaced the null values in the rating column.
 After this we can see there is column for the movies added on netflix . So we seperated the year from date_addded column and put in another column year_added using DatetimeIndex.
 This dataset shows that over the years content on netflix increases as we can see in our visualization plot, as bars keep on increasing as the year increases and same thing is happening with Tv shows.
 Then we grouped the entertainment_type column to see how many movies and Tv shows avaliable in the dataset and from that count we can see there are more movies avaliable than TV shows.
 Also, it is clear from the bar plots and pie plots that there are more movies avaliable on netflix than tv shows.
 As we can see in bar plot visualization of dataset there is almost 3 times more content added on netflix in 2017 as compare to 2016.
 Next, we made a bar plot which shows the movie and tv show which is most rated in the dataset, and from the plot we can see it is TV-MA rated movies and shows.
 From release_year, we can see that 2018 was the year where the most content is uploaded.
 One more conclusion we can make based on genre is that people like to watch more documentaries on netflix as this was the most watched genre.
 Then we checked the count of movies and shows added on netflix. and plot line graph based on it which shows the netfilx content growth over the years.
 Then we made two bar plots to see which year procduced the most content.
