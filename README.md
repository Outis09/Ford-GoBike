# Analysis of FordGoBike Share Trips

**NB:** Use these links to view the HTML files
* **[fordbike_part_I.html](https://htmlpreview.github.io/?https://github.com/Outis09/Ford-GoBike/blob/master/fordbike_part_I.html)**
* **[fordbike_part_II.html](https://htmlpreview.github.io/?https://github.com/Outis09/Ford-GoBike/blob/master/fordbike_part_II.html)**

## Dataset
The data contains information on trips made in a bike-sharing system in the greater San Francisco Bay area. It contains information on 183412 trips with 16 variables. The original dataset had some missing data therefore a copy of the data was created and nulls were dropped from the data. Using the start time, a new column was created to contain the day of the week the tri was started. Also the distance between the start and end stations for each trip was calculated using the longitudes and latitudes of both stations. The dataset used in the analysis had 165419 observations and 18 variables. The original dataset can be accessed [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).


## Summary of Findings

During analysis, I discovered an approximately linear relationship between age and distance and age and duration. As expected, I discovered a positive relationship between duration and distance. Majority of the duration is between 5 to 15 minutes.  The most trips were taken on Thursdays while Sunday had the least trips. For days of the week, the longest average trips were taken on Saturdays.  Using a line chart, I found that there were two peak periods of trips by hour of day. The first peak was in the morning from 07:00 to 09:00 and the second peak was in the late afternoon to evening from 16:00 to 18:00. These peak periods remain the same for weekdays however it is different on weekends where there is only one peak period.

I also discovered that on the average, Customers spent more time on trips and covered more distance than Subscribers.

There were more male members than there were female members and members of other gender. On the average, females spent more time on trips than male members and members of other genders. Members of other genders covered more average distance than male and female members. Also, females were averagely younger than males and members of other gender.


## Key Insights for Presentation
For the presentation, I will display the distribution of duration in minutes. I will also display the day that recorded the most trips which is Thursday and the day that recorded the least trips which is Sunday.

I will also display the line chart showing the two peak periods for the overall observations and then for the weekdays. A third line chart will be added to show the variation in peak periods for weekends.

The presentation will include the average duration and distance for each user type.
Majority of the trips take 5 to 15 minutes with a peak of 9 minutes. However, this average duration is different if the member is a Customer or Subscriber
