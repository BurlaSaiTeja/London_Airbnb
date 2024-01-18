# London_Airbnb

### About the Project:
----------------------

In the landscape of modern travel, Airbnb stands as a beacon of innovation, redefining the hospitality sector by offering unique accommodation experiences worldwide. Understanding the dynamic interplay of factors that contribute to Airbnb pricing is necessary in navigating this evolving market. Analyzing these factors not only sheds light on the essence of what shapes the cost of a stay but also holds the key to unlocking strategic insights for hosts and helps guests to make informed decisions. As the travel industry continues to transform, dissecting these elements becomes an essential compass for both hosts seeking to optimize revenue and guests aiming to find the perfect blend of value and experience in their accommodations.

The main goal of this exploratory data analysis is to identify the various factors that affect the price of the Airbnb listings, and the following are the sub-questions that will be aimed to answer:
1. Do the Airbnb prices differ between weekdays and weekends, and if so, how?
2. How do factors like distance from the city center, room type, room size, etc. affect pricing of these Airbnbs?

### Data:
---------

We have access to the Weekday and Weekend Airbnb Prices in London for conducting the analysis.

### Requirements:
-----------------

This project has been developed using the **R programming language** and the **RStudio IDE**. The implementation of this project requires the following libraries:

- ggplot2
- dplyr
- tidyverse
- broom
- mgcv
- ggmap
- metR

### Analysis:
-------------

The analysis commenced with identifying the top three variables that affect the price of a listing, distance, room type(private room/ entire apartment), and capacity of listing through a correlation plot and intuition. Subsequently, we conducted pre-processing steps and proceeded with multivariate analysis, revealing intriguing trends. Notably, the average weekend prices exhibited an approximate 1-2% increase for the entire home/apt and a 3-8% surge for private rooms compared to weekdays. Both weekday and weekend trends showcased consistent price dynamics: prices decrease with greater distance, larger rooms demand higher prices, and entire homes are marginally more expensive than private rooms. Moving to modeling, our initial attempt with a simple GAM using two variables yielded decent but not optimal results. Consequently, we adopted a more complex GAM incorporating all three variables and their interactions, resulting in our most effective model which preserved the trends of our actual data and seemingly did not overfit the data as well.

### Contributors:
-----------------

- Sai Teja Burla
- Meet Palod
- Nakul Havaldar
- Saurabh Damle

Guided By: Prof. Brad Luen
