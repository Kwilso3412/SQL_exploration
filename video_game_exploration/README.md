# SQL exploration

This is the colmination of various SQL projects in my Data Gathering and Warehousing class. It starts with cleaning dirty data and then running various queries. I have only included the most interesting queries. 

## Video Game Backlogged Exploration
The dataset used for this repository cam from the open source platform Kaggle. There are no regulatory restrictions because it is an open source platorm and anyone can use the data. There were no variable options for this dataset. The user that provided the [data from the site backlogged](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023).
The user collected the data by web scrapping from the game log/recording site Backloggedused. He used a simple data scrapping tool Beautiful Soup to extract teh data. The data is validated through multiple people on Kaggle using the data to complete their own analysis of the data. However, the data is expected to never be updated.  

I cleaned the data using R and Jupyter Notebook. The types of unit is in measurements of time, and indivudaul counts of people. To complete the cleaning I did the following:
The data was first analyzed for missing values. There were only 13 values missing so it was not significant enough to replace them. So simply filled them with NA's. I also determined there were no duplicate rows. Next I looked through to find that ratings was numeric so I converted to integar. From there I made all the column titles into lowercase and changed all the "." to "_" to make it easier when exploring the data. In a few of the rows numbers were shown as this "3.9K" to make this easier for exploration I removed the "." and then replaced the "k" with "00". Finally I converted the date from "Feb 25, 2022" to date formate "2022-02-25".

There was no specific formula it was formatted to be easy to read and simple to understand. The column names are listed below:
<br> X - The index of the variable 
<br> Title - The title of the game
<br> Release_date - When the game was released 
<br> Team - The developers of the game
<br> Rating - What players rated the game
<br> Times_listed - Number of players that listed the game 
 Number_of_reviews - The amount of reviews left by players 
<br> Genres - what genre the game is in 
<br> Summary - A summary of the game 
<br> Reviews- What the players thought about the game 
<br> Plays - How many people have played the game 
<br> Playing - How many people are currently playing the game 
<br> Backlogs - How many people have the game in their backlog 
<br> Wishlist - How many people the game in their wishlist
