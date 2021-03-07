# Beers and Breweries Project

[Jobin's Video] (https://youtu.be/IvDU3mEEXks)

The purpose of this project is to conduct analysis from multiple different angles, and make inferences based on  the  Beers and Breweries data sets that were provided.  We hope that this will fuel data driven decisions on future beer launches and beers that might need to be refreshed.

QUESTION 1
How many Breweries are present in each state?

Using the bar chart along with the heat map you can see and visualize the number of breweries per state. You can see that California and Colorado seem to have the most Breweries while states such as North Dakota and West Virginia have just one brewery.


QUESTION 2
Merge beer data with the breweries data. 
Print the first 6 observations and the last six observations to check the merged file.

Using the head function, we were able to see the first 6 observations. We were also able to see the last 6 observation using the tail function.



QUESTION 3
Address the missing values in each column.

We tidied the data by removing the NULL values.


QUESTION 4
Compute the median alcohol content and international bitterness unit for each state.
Plot a bar chart to compare.

Looking at the bar charts it seems like Maine has the highest median ABV and IBU. We can draw more inferences by studying the bar plot. 



QUESTION 5
Which state has the maximum alcoholic (ABV) beer? Which state has the most bitter (IBU) beer?

Using the original data set we found that the state with the highest Alcoholic Beverage by Volume (ABV) beer is Colorado.
The beer is called Lee Hill Series Vol. 5 - Belgian Style Quadrupel Ale having a ABV of 0.128.
We also found that the state with the highest International Bitterness Unit (IBU) beer is Oregon.
The beer is called Bitter Bitch Imperial IPA and has an IBU of 138.



QUESTION 6
Comment on the summary statistics and distribution of the ABV variable.

We can see from the data that the median of the ABV in beers in the US is around 0.056 and the  minimum is 0.001 and the maximum is around 0.128. Looking at the box plot we can see that it is normally distributed.


QUESTION 7
Is there an apparent relationship between the bitterness of the beer and its alcoholic content? Draw a scatter plot.  Make your best judgment of a relationship and EXPLAIN your answer.

There is a positive correlation between IBU and ABV. The correlation is strongest between the two when ABV is between 0.05 and 0.075. 


QUESTION 8
Investigate the difference with respect to IBU and ABV between IPAs (India Pale Ales) and other types of Ale (any beer with “Ale” in its name other than IPA). Use KNN classification to investigate this relationship. Provide statistical evidence one way or the other. 

Using the KNN classifier model we are able to predict whether a beer is a IPA or other Ale with 88.7% accuracy.We can see a relationship between IPA and other ales.




QUESTION 9
Find one other useful inference from the data that you feel Budweiser may be able to find value in.  You must convince them why it is important and back up your conviction with appropriate statistical evidence.

We grouped each beer in to five categories based on their ounces for further analysis and plotted a bar chart. Looking at the bar chart we can see that the most common beer bottle size in most states is the Stubby which ranges from 11 to 12 ounces. Some states such as Indiana and Michigan seem to have more of the Long Neck/Heritage beer size which ranges from 12 to 22 ounces. In every state the least available beer bottle size seemed to be the Bomber which ranges from 22 to 32 ounces. This information can help guide future beer launches and what sizes to prioritize in what locations.
