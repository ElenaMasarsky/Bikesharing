# Bikesharing

https://public.tableau.com/views/CitiBikeChallenge_16629291814030/NYCBikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Overview of the analysis
Last summer Kate and her friend took the trip of a lifetime. New York City for two full weeks exploring historic landmarks
like Central Park, the Statue of Liberty, and the Empire State Building.
It was a magical experience and as they flew home together they looked through their vacation photos and had a realization.
One of the key ingredients to the magic was an unlikely suspect, Citi Bike. Friends had biked everywhere which allowed them
to really get to know the city and interact with the people who live there and who are using bikes for their commutes.
A gem of an idea starts to form in their mind. What if they could start a similar bike share business for their hometown of Des
Moines, Iowa. Kate and her friend start brainstorming and a few weeks later they had a 
potential angel investor to explore a bike-share program in Des Moines. This is an exciting prospect but they know they have to think
realistically. The mechanics of making this business work might be quite different in Des Moines than in New York City. They decide
that the first step is to figure out how the bike-share business actually works in New York City. From there they'll create a
proposal on how it might work in Des Moines. 

The aim of this project is to use Citi Bike data that has been released to the public to do our bike trip analysis  in New York and
convince investors that a bike-sharing program in Des Moines is a solid business proposal.

For this analysis, we are using Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the
converted datatype, we are creating a set of visualizations to:  
* Show top starting locations;  
* Show peak hours of bike usages;  
* Show the length of time that bikes are checked out for all riders and genders;  
* Show the number of bike trips for all riders and genders for each hour of each day of the week;  
* Show the number of bike trips for each type of user and gender for each day of the week.  

## Results

![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/Top%20Starting%20Location.png)
This visualization shows that the most popular starting locations concentrated on Manhattan. And it's
predictable because Manhattan is the most densely populated of New York City’s 5 boroughs. And a lot of tourist
visit this area every day.  

![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/August%20Peak%20Hours.png)
The most frequent use of bicycles occurs from 5 p.m. to 7 p.m.  

![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/Check%20out%20times%20for%20users.png)
The most popular trip duration is less then 10 minutes.  

![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/Check%20out%20times%20by%20gender.png)
The most popular trip duration keeps the same pattern irrespective of gender.  

![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/Trips%20by%20Weekday%20for%20Each%20Hour.png)
This visualization convinces us that bicycles are not only used by tourists. Bike sharing peaks are when people travel to and
from work.


![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/Trips%20by%20Gender_Weekday%20per%20Hour.png)
The same pattern for number of bike trips for each hour of each day of the week we can observe irrespective of gender.  

![pic](https://github.com/ElenaMasarsky/Bikesharing/blob/main/Resources/User%20Trips%20by%20Gender%20by%20Weekday.png)
On this visualization we can make a conclusion that the most common customers of Citi Bike are male subscribers.  

## Summary

Summing up our analysis, we can draw the following conclusions. In August Citi Bike processed 2,344,224 rides in New York. 81% of
these rides were mada by subscribers. 65% of rides completed by male. More trips took place before and after work time during the
week days, and during weekends we observe a lot of rides through the day time.
I would suggest to perform two additional visualizations of August peak hours by customer's type to see if there's some
difference in bike sharing usage for subscribers and occasional customers.

In addition, it would make sense to find data to compare tourist traffic in both cities (New York and Des Moines) to predict
whether the usege of a bikes is going to be the same or different and in which way, if it's different.