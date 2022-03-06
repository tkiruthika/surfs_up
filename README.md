# surfs_up
## Overview
The overview of this module is to learn new tools such as SQLite, SQLAlchemy, and Flask to build SQL database structures and querying methods.
## Purpose
The purpose of this challenge is to analyze the weather data and see temperature statistics for June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
## Challenge
To analyse the temperatures for June and  December we have
  - Written two seperate queries that filters the **date** column from the **Measurement** table to retrieve all the temperatures for the months of June and December.
  - Converted the temperatures to lists.
  - Created dataframe from the list of temperatures for the respective months.
  - Generated summary statistics for the temperatures dataframe.
## Results
From the summary statistics for June and December temperatures we see that
  -  In June the minimum temperature is 64.0 but in December minimum temperature is 56.0.
  -  In June the maximum temperature is 85.0 but in December the maximum temperature is 83.0.
  -  In June the standard deviation is 3.257417 but in December the standard deviation is 3.745920.
  
  
  ![1](https://user-images.githubusercontent.com/95719819/156914933-7b0f8ae9-f6bc-4195-9c73-e2616353074d.png) ![2](https://user-images.githubusercontent.com/95719819/156914932-64438bdb-115f-4d60-8ded-03dccdd74096.png)
  
 ## Summary
 With the above results we can summarize that the temperature in Oahu is relatively the same throughout the year as the mean temperatures are almost the same for June and December. This shows that icecream shop business will be sucessful in Oahu.

But for surfing to be sucessful we should analyse the precipition statistics for June and December. The Query and the precipitation statistics are displayed below.

By analyzing the precipitation we can summarize that Oahu has more rain in winter than in summer but the mean values show that there is no continuous rainfall. So we can conclude our analysis as surf and ice cream shop business in Oahu is sustainable year-round.
 
![3](https://user-images.githubusercontent.com/95719819/156916023-e4241722-b82f-40ef-b6c8-7cf523c9a493.png)

![4](https://user-images.githubusercontent.com/95719819/156916022-e54c60b4-33c9-400d-8e44-24b0213dbe0b.png)
