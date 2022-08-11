# Bike Sharing
## Overview
I took a two-weeks trip to New York City with my friend exploring historical landmarks. My realization on this trip was that one of the key ingredients that made the trip magical was "Citi Bike". I biked everywhere which allowed me to really get to know the city and interact with the people who live there and also use bikes for their commute. Being business minded, I would like to start a similar bike-sharing business for my hometown of Des Moines. I have come across a potential investor who might be interested in providing seed funding to explore a bike-sharing program in Des Moines. The mechanics of making this business work will be quite different in Des Moines than in the hustle and bustle of New York City. I have therefore, decided to first of all find out more about how the bike-sharing business works in New York City then I create a proposal of how it might work in Des Moines.

In this project, I will use visualizations that tell a story to present a business proposal for the bike-sharing company using the data analysis visualization tool, Tableau. Worksheets, dashboards, and stories will be created to visualize key data from the New York Citi Bike dataset.

## Results
The data of the Citi Bike program in New York City is contained in a CSV. The August 2019 data to be specific, was used because there is likely more traffic during the summer months. From my visualizations with Tableau, the number of rides for August 2019 was **2,344,224**. 

I continued by determining the number of short-term customers and annual subscribers to the Citi Bike service. This will help predict the types of customers to be expected for a similar bike-sharing company in Des Moines. The proportion of short-term customers to the annual subscribers was found using a pie chart. The number of customers was **443,865** while the number of subscribers was **1,900,359** which shows that the percenatage of riders who are customers is 19% and the percentage of subscribers is 81%.

Another pie chart was created to know the gender breakdown of Citi Bike riders. From this pie chart we were able to discover that males use bike sharing the most. The number of males taking the rides was 1,530,272. That of females was 588,431 and 225,521 were unknown gender. 

Two symbol maps were created to find the highest-traffic locations for both starting and ending a bike journey among Citi Bike customers. These graphs helped to understand where people use Citi Bike and where they drop off the bikes.

To have a fair idea of some of the costs that might come up while running the business, bike maintenance was considered as one of the biggest expense. Bikes that are used most frequently will probably be the ones that require the most maintenance. With this knowledge, bikes with the highest number of rides were determined by creating a treemap which helped us get an idea of how often each bike is used.

A packed bubbles visualization was also created to discover the utilization of each Citi Bike in the month of August. This will allow us to view the total usage time per bike, as well as which bikes are used the most frequently, which will give further insight into which bikes may need repairs. Most of the above mentioned graphs are shown in the dashboard below:

![image8](https://github.com/GerlechJen/bikesharing/blob/main/Images/dashboard.png)

The peak usage hours for the month of August was figured out using a horizontal bar chart. This will help the investors get a ballpark estimate of how many bikes might be needed in Des Moines and also figure out during which parts of the day bikes will be needed the most. This way, if maintenance is required on a bike, knowing the peak usage hours will help make plans on the best time to do that. The bar graph which displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August is shown below:

![image1](https://github.com/GerlechJen/bikesharing/blob/main/Images/August%20Peak%20Hours.png)

From the above graph, the top riding hours were during morning rush hours between **8 AM** and **9 AM** and end-of-workday hours between **5 PM** and **6 PM**. The most idle hours were between **1 AM** to **5 AM** so bike maintenance can be performed during these idle hours.

An area chart was created next, to find the average duration of a bike ride by age. This will help set expectations for trip duration in Des Moines.

![image2](https://github.com/GerlechJen/bikesharing/blob/main/Images/Average%20Trip%20Duration.png)

This chart shows that the bikeshare usage covers all age demographics, from teenagers to the elderly. The highest trip duration recorded was for birth year 1891 with a trip duration of 2,692 folowed by birth year 1969 with a trip duration of 2,146. Overall, the average length of trips by the younger generation covers a larger area than that of the aged. This shows that the youth generally enjoy taking much longer bike rides than the old.

Bike trip analysis was performed by plotting a line graph that shows the length of time that bikes are checked out for all riders and genders.

![image6](https://github.com/GerlechJen/bikesharing/blob/main/Images/Checkout%20Times%20for%20Users.png)


The results of the above graph showed that majority of trips taken on Citi Bike bikes are for less than an hour. Most trips are under 30 minutes, with a significant drop in number of rides after an hour. Trip duration of 5 minutes had the highest number of rides of **146,752**

Another line chart that shows the number of bike trips for all riders and genders for each hour of each day of the week was plotted. 

![image7](https://github.com/GerlechJen/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.png)

The above results emphasised how the less than an hour trip durations are mostly taken by male riders, followed by female riders, with the least being those with unknown or unspecified gender. 

Continuing further, a graph was drawn to show the number of bike trips by weekday for each hour of the day as a heatmap.

![image3](https://github.com/GerlechJen/bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20Hour.png)

The visualization of this graph confirms once again that, there is heavy bike usage during weekday commute times of 8AM and 9AM then 5PM and 6PM. For weekends, the usage is spread throughout the middle of the day. One perculiar thing observed is the low bike usage during Wednesday's end-of-day commute. It will be a great idea to explore reasons for this. For instance holidays falling on Wednesdays. But it could also be just an arbitrary inconsistency. One consistent observation though is that the low-usage hours is between 1AM to 5AM every day of the week.

Another graph was drawn to show the number of bike trips by gender for each hour of each day of the week as a heatmap.

![image4](https://github.com/GerlechJen/bikesharing/blob/main/Images/Trips%20by%20Gender%20.png)

This graph confirmed the previous observation that most rides are by male riders, followed by females then unknowns. The peak times observed for the trips were more visible for the male riders. 



A final heatmap that shows the number of bike trips broken down by gender and usertype for each day of the week was plotted.

![image5](https://github.com/GerlechJen/bikesharing/blob/main/Images/User%20Trips%20by%20Gender.png)

This visualization shows how majority of the riders are male subscibers.This graph solidifies our earlier analysis that showed that most of the riders are subscribers. 

## Summary

In conclusion, the usertype of Citi Bike bike-sharing service is mostly subscribers.  Of all the users, male subscribers are the most and provide regular income to the business. The usage of the bikes peak during weeekday morning and evening commute times of 8 AM to 9 AM and 5 PM to 6PM respectively. The usage of the bikes is at the lowest between 1 AM and 5 AM everyday. On weekends, the usage is spread throughout the middle of the day from around 9 AM to 7 PM.

If I were to pursue further analysis given the data provided, I would perform these two visualizations:

1. A bar graph to show the top 10 trip starting and ending locations.
2. An area graph to show the number of rides versus birth year to know which age groups often take rides. 

A Tableau story for the visualizations of this data was developed and it can be seen by clicking [here](https://public.tableau.com/app/profile/jennifer.anno.kusi/viz/NYCCitiBikeStory_16602520805310/Story1?publish=yes).

----

**Completed by:** Jennifer Anno-Kusi

**Email:** jannokusi@gmail.com 
