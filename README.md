# Netflix-data-cleaning-and-visualisation-project
Netflix is a popular streaming service that offers a vast catalog of movies, TV shows, and original contents. 
The data consist of contents added to Netflix from 2008 to 2021. The oldest content is as old as 1925 and the newest as 2021.
This project provides the valuable insights for the netflix based on the content being added by cleaning the data and 
providing visualisations.
1. Understanding what content is available in different countries
2. Analysis of addition of content on yearly basis and how it has increased.
3. Understanding of rating distribution on Netflix
4. Does Netflix have more focus on TV Shows than movies in recent years.
5. Understanding the increase in addition of content on yearly basis.

# Python libraries to run the project:
1. importing *pandas* for data cleaning and manipulating
2. importing *numpy* for numerical operations
3. importing *seaborn* for data visualisation
4. importing *matplotlib* for graphs and visualisations
5. importing *calendar* for fetching month from date. 

## How to use the project for gaining valuable insights
Using *Jupyter Notebook* for the cleaning and visualisation

## Data Cleaning and Manipulation:
PSB major points covered in Data cleaning and manipulation. Details are provided with code in the Jupyter notebook
1. File reading using read_csv function of pandas library.
2. Dealing with null values for required columns and dropping the columns where necessary.
3. Making the date_added column uniform
4. Converting the duration if given in hours for  movies and separating the column for TV shows.
5. Adding rating_category column for better description of the ratings for the users.

## Business values from Data Visualisation:
PSB major points covered in Data Visualisation. Details are added with graphs in the Jupyter notebook.
1. Distribution of shows in Netflix: 
Helps to understand the focus of content in the Netflix.
2. Rating distribution on Netflix:
This graph indicates the content age band, on how it is classified in terms of rating.
3. Top 10 content count across countries by content type:
Helps to understand about the customer base from country perspective and based on content type.
This helps the business to decide what contents to stream in which country to have higher content value.
4. Distribution of release years:
This graph provides analysis of increase in release 
of content over the years and how TV shows have gained popularity to invest more on the Tv shows as well as movie.
5. Distribution of Rating categories for movies and TV shows:
Focused on the age category to understand age rating of majority shows.
6. Trend of yearly added content:
With heatmap understanding the yearly added content count and about the timelines to understand the trend of content addition.