# Project description
The data was scraped from Immoscout24, the biggest real estate platform in Germany.  The data set contains offers from the dates 2018-09-22, 2019-05-10 and 2019-10-08. There in different infomation regarding region, total rent, base rent, has a balcony or not, number of rooms, heating type, etc.  It also has two variables containing longer free text descriptions: description with a text describing the offer and facilities describing all available facilities, newest renovation etc. I have analyzed some of the variables and compared them with each other after cleaning the data first. 

# Questions

Read the data and see if there are any missing values. If yes please clean the dataset. 

1. What is the average rent for apartments in different regios? Visualize the results
2. Is there any relationship between base rent and total rent? 
3. Visualize the relationship between number of rooms and total rent.
4. Does the presence of a balcony impacts the price of the apartments?

# Answers
All the answers are presented in jupyter notebooks using python language and presented in plots to have a better visual view. From the results presented we can see that the average rent changes based on region. We have Hamburg with the highest average rent and Thüringen with the lowest. 
Basen on the plots and calculations base and total rent have a linear relationship. 
The same happens between number of rooms and total rent. The have a linear relationship. In the other hand, the presence of a balcony did not have any huge impact in the prices of apartments. 

# Consclussions

Considering that I have chossen a really large dataset, of course there are many other factors that I can take into consideration and analyze. But based on my analysis I can confidentially say that the total price of apartments changes when the base rent increases or decreases. A really important indicator is the number of rooms too that has an impact on total price.  