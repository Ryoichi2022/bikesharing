Challenge 14
# NY CitiBike

## 1. Overview of analysis
### Project overview
The New York City deploys a number of CitiBike all over the city, which allows visitors or travelers to move around to know one of the largest cities in the world. CitiBike also helps people that live in NYC with their daily commutes.
The research is going to be conducted to figure out how the bike-share business actually works in the city of New York and to determine whether the similar mechanism would be feasible in other cities in the United States, such as Des Moines, Iowa. Then, the analysis will be part of a proposal to potential investors that might be interested in funding a bike-share program.

#### The entire analysis report can be accessed through the following link.
### [Link to NYC CitiBike Analysis Report](https://public.tableau.com/app/profile/ryoichi.nakayama/viz/NYC_Citibike_Challenge_16626042461980/Analysis_Report)


### Data summary
The dataset for the analysis was gathered during August 2019. It is likely the month when more people go outside and ride a bike than in any other months of the year. The total number of rides throughout the period was 2,344,224, and every ride data contains information such as duration, start and end time with location (station name and coordinates), bike ID, and bike year. 65% of the rides were by male, and 25% were by female. In addition, bike-share subscribers accounted for 81% of the total rides.


## 2. Results
### Where CitiBike is used
The location map shows only stations that respectively counted 10,000 rides or more during the period by default. The popular starting stations are located in the same area as the popular ending stations, including Pershing Square North, E17 St & Broadway, Broadway & E22 ST, E24 St & Park Ave S, W21 St & 6 Ave, and Broadway & E14 St, to name a few. They are in the southern part of Manhattan.

![](https://github.com/Ryoichi2022/bikesharing/blob/main/Where_used.png)

### How long CitiBike is used
As popular stations are concentrated in a certain area, ride duration would not be expected to be very long, which is supported by the data. The mode of the duration was 5, which means five minutes and more but less than six minutes. Also, 99% of the rides were less than one hour. Although far more number of males use CitiBike than females, the shape of the line charts resembles each other between male and female with frequent duration being 4, 5, 6, and 7.

![](https://github.com/Ryoichi2022/bikesharing/blob/main/How_long_used.png)

### When CitiBike is used
The chart indicates that the darker the color, the more frequently CitiBike is used. The research reveals that more people in the NYC take CitiBike during weekdays between 7 and 10 in the morning as well as 5 and 8 in the evening than any other part of the day. On Saturdays and Sundays, on the other hand, utilization appears high during daytime, or between 10 AM and 8 PM. Additionally, subscribers tend to use CitiBike more during weekdays, while customers use it more on Saturdays and Sundays.

![](https://github.com/Ryoichi2022/bikesharing/blob/main/When_used.png)

## 3. Summary
### Common use of CitiBike
In general, CitiBike is utilized more during weekdays by subscribers, who pay in a regular basis to continuously access the service. These people will likely ride CitiBike for their daily commutes. The bikes appear to be more frequently used within the New York City downtown area. Customers, who represents approximately 20% of the rides, use CitiBike as well, and their uses are counted more during weekends. They may mainly use the bike for leisure purposes.

### Additional visualizations
The following visualizations could help understanding of how the CitiBike business works in the New York City.

* To understand ride duration by subscribers and customers respectively, ride duration could be visualized by user type in addition to by gender. It will help further analysis to determine whether subscribers and customers use CitiBike differently in terms of duration.
* The markers on the location maps could be colored differently by weekday. People may get on Citibike for different purposes, and busy stations during weekdays will be different from those during Saturdays and Sundays.
