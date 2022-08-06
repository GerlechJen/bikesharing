# Bike Sharing
## Overview
I took a two-weeks trip to New York City with my friend exploring historical landmarks. My realization on this trip was that one of the key ingredients that made the trip magical was "Citi Bike". I biked everywhere which allowed me to really get to know the city and interact with the people who live there and also use bikes for their commute. Being business minded, I would like to start a similar bike-sharing business for my hometown of Des Moines. I have come across a potential investor who might be interested in providing seed funding to explore a bike-sharing program in Des Moines. The mechanics of making this business work will be quite different in Des Moines than in the hustle and bustle of New York City. I have therefore, decided to first of all find out more about how the bike-sharing business works in New York City then I create a proposal of how it might work in Des Moines.

In this project, I will use visualizations that tell a story to present a business proposal for the bike-sharing company using the data analysis visualization tool, Tableau. Worksheets, dashboards, and stories will be created to visualize key data from the New York Citi Bike dataset.

## Results
The data of the Citi Bike program in New York City is contained in a CSV. The August 2019 data to be specific, was used because there is likely more traffic during the summer months. From our visualizations with Tableau, the number of rides for August 2019 was **2,344,224**. 

I determined the number of short-term customers and annual subscribers to the Citi Bike service. This will help predict the types of customers to be expected for a bike-sharing company in Des Moines. The proportion of short-term customers to the annual subscribers was found using a pie chart. The number of customers was **443,865** while the number of subscribers was **1,900,359**.

Another pie chart was created to know the gender breakdown of Citi Bike riders. From this pie chart we were able to discover that males use bike sharing the most. The number of males taking the rides was 1,530,272. That of females was 588,431 and 225,521 were unknown gender. 

Two symbol maps were created to find the highest-traffic locations for both starting and ending a bike journey among Citi Bike customers. These graphs helped to understand where people use Citi Bike and where they drop off the bikes.

To have a fair idea of some of the costs that might come up while running the business, bike maintenance was considered as one of the biggest expense. Bikes that are used most frequently will probably be the ones that require the most maintenance. With this knowledge, bikes with the highest number of rides were determined by creating a treemap which helped us get an idea of how often each bike is used.

A packed bubbles visualization was also created to discover the utilization of each Citi Bike in the month of August. This will allow us to view the total usage time per bike, as well as which bikes are used the most frequently, which will give further insight into which bikes may need repairs.

The peak usage hours for the month of August was figured out using a horizontal bar chart. This will help the investors get a ballpark estimate of how many bikes might be needed in Des Moines and also figure out during which parts of the day bikes will be needed the most. This way, if maintenance is required on a bike, knowing the peak usage hours will help make plans on the best time to do that. The bar graph which displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August is shown below:

![image1](https://github.com/GerlechJen/bikesharing/blob/main/Images/August%20Peak%20Hours.png)

From the above graph, the top riding hours were during morning rush hour between **8 AM** and **9 AM** and end-of-workday hours between **5 PM** and **6 PM**. The most idle hours were between **1 AM** to **5 AM** so bike maintenance can be performed during those hours.

An area chart was created next to find the average duration of a bike ride, by age. This will help set expectations for trip duration in Des Moines.

![image2](https://github.com/GerlechJen/bikesharing/blob/main/Images/Average%20Trip%20Duration.png)

This chart shows that the bikeshare usage covers all age demographics, from teenagers to the elderly. The highest trip duration recorded was for birth year 1891 with a trip duration of 2,692 folowed by birth year 1969 with a trip duration of 2,146. Overall, the average length of trips by the younger generation covers a larger area than that of the aged. This shows that the youth generally enjoy taking much longer bike rides than the old.

Bike trip analysis was performed by plotting a line graph that shows the length of time that bikes are checked out for all riders and genders.

![image6](https://github.com/GerlechJen/bikesharing/blob/main/Images/Checkout%20Times%20for%20Users.png)


The results of the above graph showed that majority of trips taken on Citi Bike bikes are for less than an hour. Most trips are under 30 minutes, with a significant drop in number of rides after an hour. Trip duration of 5 minutes had the highest number of rides of **146,752**

Another line chart that shows the number of bike trips for all riders and genders for each hour of each day of the week was plotted. 

![image7](https://github.com/GerlechJen/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.png)

The above results emphasised how the less than an hour trip durations are mostly taken by male riders, followed by female riders with the least being those with unknown or unspecified gender. 

A graph was drawn to show the the number of bike trips by weekday for each hour of the day as a heatmap.

![image3](https://github.com/GerlechJen/bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20Hour.png)

This visualization shows how majority of the riders are male subscibers.This graph solidifies our previous analysis that showed that most of the riders are subscribers. 

There are one or two additional charts available in the Tableau analysis, but they tell pretty much the same story that has already been displayed above.

The visualization of this graph confirms once again that, there is heavy bike usage during weekday commute times of 8AM and 9AM then 5PM and 6PM. For weekends, the usage is spread throughout the middle of the day. One perculiar thing observed is the low bike usage during Wednesday's end-of-day commute. It will be a great idea to explore reasons for this. For instance holidays falling on Wednesdays. But it could also be just an arbitrary inconsistency. Also, it is still observed that the low-usage hours is between 1AM to 5AM every day of the week.

Another graph was drawn to show the number of bike trips by gender for each hour of each day of the week as a heatmap.

![image4](https://github.com/GerlechJen/bikesharing/blob/main/Images/Trips%20by%20Gender%20.png)

The results showed that

A final heatmap that shows the number of bike trips broken down by gender and usertype for each day of the week.

![image5](https://github.com/GerlechJen/bikesharing/blob/main/Images/User%20Trips%20by%20Gender.png)

The results showed that








## Summary

A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.


In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.

The Tableau story can be seen, by clicking 




----

**Completed by:** Jennifer Anno-Kusi

**Email:** jannokusi@gmail.com 
