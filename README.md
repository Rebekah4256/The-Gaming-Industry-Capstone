# The-Gaming-Industry-Capstone
  This is the capstone project for my Data Analytics course, comparing companies in the gaming industry.

  The data I will be using for my capstone is the main file from the Video Game Sales & Metacritic Intelligence 1980–26 dataset on Kaggle (https://www.kaggle.com/datasets/meruvakodandasuraj/video-game-sales-and-metacritic-intelligence-198026). This data was created by Meruva Kodanda Suraj.

  From the information, I would like to see how much the publishers made in the years covered, and whether the platform on which they released the games would affect that. Another thing I want to see is how much gameplay you get for the game's release price. The last thing I want to figure out is how user reviews compare to critics' reviews, and whether the ESRB (Entertainment Software Rating Board) would make that difference.

  Before answering my questions, I need to get a clear view of the data. To do this, I will need to ensure there is no missing or duplicate data and examine the data.

  Now I'll start looking more into the actual data, starting by seeing how many games were released on each exact platform. In this data, it would seem that most of the games were released on the PC, with the NES (Nintendo Entertainment System), released in 1986, is second, and the least is the Nintendo Switch 2, which makes sense because it is the newest released console.

 Additionally, I would like to see how many games were released in each year. So most games were released in 2011 and 2019, but surprisingly, the next is 2026, and it's only a few months into the year.

 Another thing I would like to look into is the publishers' regions and the number of games they have published. Looking at the results, most publishers are from the US, and the next most are from Japan. And SAGA has published the most games.

 Subsequently, I would like to see which publisher made the most money globally. SEGA, Nintendo, and Sony Interactive have made the most globally, and Motion Twin has made the least.

 Next, I would like to see which game made the most and what made the least. FIFA 2026 made the most, and The Elder Scrolls XI: Dark Below made the least.

 Next, I'm looking at how long it would take, in hours, to reach 100% (complete everything there is to do in the game) in every game the developer made. To 100% all of the games SEGA has ever made, it would take 121477 hours, or 5061 days, or almost 14 years.

 Next, I wanted to see which developer had the longest average time to 100% one of their games. Coffee Stain has, on average, the longest games to 100% at 100 hours on average, and Unknown Worlds has the shortest at 79 hours.

 Next, I want to see how much, on average, a game costs on the console it was released on, how much the games made globally, how many hours it would take to 100% it, and how many consoles were released. Looking at it, Mobal games have the highest global sales even though their average price is about 2 dollars. Why they are the highest earners is because of in-game purchases, whereas something like the Game Boy Color only made the lowest because of the lack of games, having only 750, and the average launch price for the game being 35 dollars.

 Next, I wanted to see the same thing, but this time, the developer, not the platform. Looking at the developer, they have the longest hours to 100% is Coffee Stain, and their average launch price is 40, and their global sales are 10722.

 Next, I would like to graph some of the things I found interesting. So, to start, I would like to create a bar chart showing how much each publisher made in total, with a line showing the average time it took to reach 100% of their games on average. To do that, I first need to create a new data frame with only the information I want to use and aggregate it to prepare it for the graph. The graph shows that how long it takes to complete the game does not affect how much the company makes in the global market.

 Next, I would like to see how much the whole gaming industry made in the years. The graph shows that sales have been increasing steadily over the years.

 Next, I would like to compare profits across platform types. First, I need to create a data frame containing the aggregated data I will use: year, platform type, and global sales. Next, I need to create a pivot table so the graph has a separate line for each platform. Now it's time to make a graph showing how much each platform type made over the years, along with the games sold on each platform. This graph shows that almost all platform types have remained the same over the years, except for the mobile game platform, which has increased significantly in the past few years.

 The final thing I would like to look at is how the ESRB Rating compares to how people rate the games, and how many Game of the Year awards they nominated for and received. This shows that, on average, the ESRB rating does not affect how the average person or critics view the game, but it does seem to affect whether the game is nominated or wins Game of the Year.
