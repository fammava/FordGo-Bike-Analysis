# Ford GoBike System Data Exploration
## by Emmanuel Waribo Otiti


## Dataset

>This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Looking at Bay Wheels's trip data for public use in the year 2019, the dataset can be gotten from Here. The dataset contains 183412 rows with 16 columns which are duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip.


## Summary of Findings

> In the exploration, I did some cleaning and tidying in the data, which made it posible to discuss the different variable distributions. I engineered new variables: month, customer decade, start_date, end_date, and age from existing variabes, with the trip duration being further splitted into minutes and hours. I discovered that older users above 85 years do not use the system for duration higher than 100 minutes. Furthermore, even when it was discovered that subcribers were higher than customers, in the plot(3) of bivariate exploration it was discovered that customers had longer time durations in their trip as compared to subcribers.

Some features showed Customers to Subscribers differences as seen in the multivariate exploration which strengthened some of the patterns discovered in the previous bivariate exploration as well as univariate exploration, the relationship between the multiple variables plotted were visualized together with the information being presented. The high concentration on rush hours Monday through Friday, indicates FordGo bike system use is primarily for work commute. However, customers tend to have more trip durations than customers.


## Key Insights for Presentation

> Age of customers and duration of ride in minutes can be used to better understand how the FordGo bike system operates and works. If improvements are needed to improve number of rides for different age groups. From the plot, it shows that customers within the age brackets of 20 to 85 usually have duration of rides that last less than 100 minutes. With the duration of rides reducing drastically with age groups less than 60. The FordGo bike system have a handful of users that are above 80, which means that if they are to see an increase in this number they are to provide special services to the age groups.

>Routes is the destination(end station name) from the starting(start station name) points, this plots depicts the total average time of the journey in hours. The longest route average time is from 11th St at Natoma St to 16th St Depot station which takes an average of 23 hours, followed Scott St at Golden Gate Ave to McAllister St at Baker St station with an average of 20 hours time duration. FordGo bike system can increase the number of bikes that ply these routes in order to generate more revenue.