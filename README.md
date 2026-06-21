## About the project
For this project, I analyzed a dataset containing the best movies of all time to identify trends and patterns. Titles include movies like Spiderman, Pretty Woman, Black Panther, Wonder Woman, Pirates of The Caribbean, Avatar. Most of the movies are highly rated by IMDb, Rotten Tomatoes, Vudu, Metacritic etc.

The time frame of the dataset is from 1989 to 2021. The dataset is from @nimcool on data.world.

## Clean
Cleaning was done with both Spreadsheets and R. Spreadsheets was used to add the release years to the titles, correct figures, remove an incorrect row, remove a duplicate, and correct a date. 

1) The release years were added to the titles because figures with similar titles added up when uploaded to Tableau. Also, adding the release years to the titles made it easy to spot patterns. For example, 4 out of the bottom 10 lowest grossing movies were movies released in 2020, this was due to the COVID-19 Pandemic. 

2) Most of the budget figures and gross figures were obtained from Wikipedia. Some of the figures might not be exactly accurate. It was not stated on Wikipedia if the budget figures included print and advertising cost. Also, some of the budget figures were in ranges. The figures in the dataset that were within the ranges in Wikipedia were not changed, only the figures that were below or above the ranges or different from what is on Wikipedia were changed. It was also not stated if the gross figures included other revenue sources like DVD sales, TV and international rights, streaming platforms etc.  And the gross figures were rounded up.

3) One movie was removed from the dataset because the budget figure and gross figure were similar and the budget figure was not on Wikipedia or other sites. A movie was recorded twice, one of them was removed. Another movie had an incorrect date which was corrected.

## Findings

**Budget vs. Gross**
<img width="1314" height="597" alt="bdg vs gro" src="https://github.com/user-attachments/assets/8f386a53-81e1-4a11-8568-d72715b7ef84" />
There is a positive relationship between budget and gross.

**Highest Budget vs. Highest Grossing**
<img width="1499" height="1199" alt="Highest Budget vs  Highest Grossing" src="https://github.com/user-attachments/assets/2c0011e1-ec63-4a91-80b8-ac5dccad7f4c" />
Avengers: Infinity War-2018, Avenger: Endgame-2019 and Star Wars: The Force Awakens-2015 appeared on both the top 10 highest budget movies chart and the top 10 highest grossing movies chart.

**Lowest Budget vs. Lowest Grossing**
<img width="1499" height="1199" alt="Lowest Budget vs  Lowest Grossing" src="https://github.com/user-attachments/assets/622e46a5-fa57-4bff-bad7-a31910471f88" />
The Crying Game-1992 and The Father-2020 appeared on both the bottom 10 lowest budget movies chart and bottom 10 lowest grossing movies chart. Three other movies released in 2020 appeared on the bottom 10 lowest grossing movies chart.

**Trends Over Time**
<img width="1499" height="1199" alt="Trends Over Time" src="https://github.com/user-attachments/assets/081ccdbb-300d-4095-af6a-247eb0c72f5f" />
Up until 2020, there was a steady increase in average movie budget and average movie gross. 

There was a significant decrease in the number of movies, average budget and average gross in 2020.  The number of movies dropped from 20 to 11, the average budget dropped from $138,975,000 to $89,227,273 and the average gross dropped from $705,990,000 to $207,210,986. The differences are quite huge.

**Age Ratings**
<img width="1499" height="1199" alt="Age Ratings" src="https://github.com/user-attachments/assets/6f722070-7841-4cd9-a6d3-56545e5f3230" />
General rated movies had the lowest number of movies but had the second highest average budget and second highest average gross. PG-13 had the highest number of movies, highest averarge budget and highest average gross. PG and R rated movies ranked second and third in number of movies, and third and fourth in both average budget and average gross.

**Movie Release Seasons**
<img width="1314" height="597" alt="movie release seasons" src="https://github.com/user-attachments/assets/124405a9-8af0-4293-b7a3-849dcf448f75" />
Most of the movies were released mid-year and end-of-year.

Explore the [interactive dashboard](https://public.tableau.com/views/BestMoviesofAllTime1989-2021/successfulunsuccessfuldashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) that highlights the successful movies and unsuccessful movies.






