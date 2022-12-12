# Netflix Movies and TV Shows
 Netflix is one of the most popular digital streaming media service providers today. Netflix provides streaming services for movies and tv shows from various countries in the world. As a digital media with many users, Netflix also has a very large amount of data.This dataset consists of tv shows and movies available on Netflix as of 2020. In this jupyter notebook, I will perform data visualizations using Netflix data using matplotlib, seaborn and pandas. 
  
 ## Datasets
 * The netflix dataset we have used is from kaggle, which is https://www.kaggle.com/code/aayushmishra1512/netflix-data-analysis-and-visualization/notebook
 * For ratings we used OMdb api http://www.omdbapi.com/
 * For csv data we used netfilx_titles.csv
 
 ### Dataset Attributes :
* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Release year of the move / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genre
* description : The summary description

 
## Data cleaning
 
 In this jupyter notebook we used netfilx_titles.csv, which contains movies and tv shows titles, show id, duration, years, ratings, directors, cast as columns we we are going to use further in the visualization in jupyter notebook using pandas library. First thing we did was we dropped the null values and and dropped the unnecessaary columns to make the data more presentable and also replaced the columns values wherever its neccessary. We column changed the column names of 'type' to 'entertainment type' and 'listed in' to 'genre' to make it more understandable.
 
## Question1: What type of content is avaliable on netflix?
 
 To answer this question , we made two visualizations, one is pie plot and other one is bar plot. Here we grouped the column 'entertainment type' and used count() function on it to get the count of number of movies and Tv shows avaliable to watch on netflix. After that we created 2 plots using this information one is pie plot and other one is bar plot, from which we can see clearly that there is more movies avaliable on netflix than Tv shows.
 
 ![image](https://user-images.githubusercontent.com/28380164/207076881-04d61dcb-64f7-44c0-a0a5-cb66edcd6559.png)
 ![image](https://user-images.githubusercontent.com/28380164/207077142-89c4c436-bea3-465d-8976-cb93bd7338c8.png)
 
 ## Question2:  What are the most popular genre on netflix?
 
 To answer it, we use column 'genre' and find the top 10 movies and tv shows added on netflix as per genere. Once we get the data we created two visualizations, on is bar and other one is pie plot. Form which we can see that international movies are most popular genre in our dataset followed by Drama and Comedy.
 
 ![image](https://user-images.githubusercontent.com/28380164/207078928-03635c29-1ffd-4c1b-b5a9-252fcef746fa.png)
![image](https://user-images.githubusercontent.com/28380164/207078977-4ee8e7a4-5a64-461b-8086-1fb6c10b722f.png)

 
## Question3: How has netflix content grown over that years?

We came up with three visualizations for this question one is line plot and other two are bar plots. Here we have compared the year on which content added on netflix to their count. From that we can see that their is steady growth in content on netflix and we can see that 2019 was the year where most content was added. And using the same data we created two bar graphs which are for movies and Tv shows 

![image](https://user-images.githubusercontent.com/28380164/207080174-cdeb4b9c-c4af-455e-8ccb-7fa45cd81851.png)
![image](https://user-images.githubusercontent.com/28380164/207080362-caf83f45-da63-45b1-8669-d892bbafa9c0.png)
![image](https://user-images.githubusercontent.com/28380164/207080457-62a6dc2c-c810-42c5-90bf-5e422882a841.png)

## Question4: Which country has highest number of titles on netflix?

For this question we came up with two visualizations one is pie plot and other is bar plot. First we comapred the counties to the titles and then ploted a bar plot which shows us US was producing most number of titles followed by India and United Kingdom . Same thing we can see in Pie Plot as we have 56% titles are available in United States followed by India and United kingdom.

![image](https://user-images.githubusercontent.com/28380164/207085219-99637709-4110-45bb-97bc-9ea250278c65.png)
![image](https://user-images.githubusercontent.com/28380164/207085301-9c12dac0-9979-49e5-a109-ec9a402a6d85.png)

## Question 5: What are the most popular maturity ratings on netflix?

To answer this question we created visulaizations using rating and rating count. And we have created two visualizations which are Tv-Ma for both Tv shows and Movie, and other one is scatter plot showing same results TV-Ma most avaliable.

![image](https://user-images.githubusercontent.com/28380164/207086516-1f79f989-64ae-4b2b-9a76-d7166b0ec5cc.png)
![image](https://user-images.githubusercontent.com/28380164/207086620-40f55cb0-48fd-4fd0-8d8d-2b24af936728.png)

## Question 6: What are the top 10 hightest and lowest rated titles based on IMDB ratings?

To answer this question we use OMdb api to get the data for IMDB ratings. Once we got the ratings we showed that the top 10 and bottom 10 based on IMDB ratings.From that we can see TV Show 'Equestria Girls: Tales of Canterlot High' was highest rated and movie 'Nasha' was the lowest rated movie avaliable on netflix.

![image](https://user-images.githubusercontent.com/28380164/207088836-db0a4a3a-9464-46ab-8889-27e9cf6d6d9b.png)

![image](https://user-images.githubusercontent.com/28380164/207088909-783dcdca-ce82-4bde-a308-be6c9b730f65.png)










 
