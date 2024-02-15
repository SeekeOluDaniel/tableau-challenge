# Tableau-Challenge
 Week 18 Assignment

### Introduction
The objective was to build a set of data reports and visualizations (dashboards) for the New York Citi Bike program. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage. As expected, city officials have questions about the performance and improvement opportunities of the program. So this task is really about providing answers to those questions, and uncovering actionable insights.

My approach was to compare activities and metrics between two months: September and December, which represent two major seasons: summer and fall/winter.

### Data Description
I downloaded and merged data sets for September and December 2023 bike trip data, from the Citi Bike website ()
The following fields are available in the data, and I changed the column labels to reflect the data using below names:
Ride ID
Bike type (classic or electric)
Start Time
End Time
Trip Duration (in minutes)
Start station name
Start station ID
End station name
End station ID
Start latitude
Start longitude
End latitude
End Longitude
Rider Type(Member or casual ride)

### Tools/Libraries
1. Excel
2. Pandas
3. Tableau Public desktop

### Analysis Report
This report will focus on and seek to provide insights along the following sub-topics:

#### Ridership
There were more than 3.2 million rides in September, with a total trip duration of 47.8 million minutes and average trip duration of 14.9 minutes per trip. These numbers declined significantly in December - number of rides reduced by 37.7% to 1.9 million rides in December 2023; with a total trip duration of 24.5 million minutes (48.8% decrease) and average trip duration of 12.3 minutes per trip. 

This is likely due to weather/temperature changes as we transitioned from late summer in September to fall/early winter in December.

#### Membership
Riders are categorized as either members or casual riders, with the members having purchased or renewed various types of passes; and casual riders only paying for trips on a pay per use basis.
In September 2023, casual riders accounted for 21.3% of the total number of rides and members, 78.6%. Casual ridership decreased in December to 18.4% of the total ride count.

#### Bike Type
Classic bikes remained more popular than electric bikes in both months under review.

#### Peak vs Off-Peak Hours
Peak hours vary slightly from season to season but generally follow the same trends. In the summer (September), about 50,000 rides start around midnight, steadily declining through the night and picks up between 4am and 5am, with a sharp increase from 5am and reaching a morning peak around 8am. The number of checked bikes exceeds the morning peak around 2pm and rises sharply until 6pm, which is the time with the highest number of rides.  

In the fall/early winter (December), about 30,000 rides start around midnight, steadily declining through the night and picks up between 4am and 5am, with a sharp increase from 5am and reaching a morning peak around 8am. The number of checked bikes exceeds the morning peak around 2pm and rises steadily (albeit at a much slower rate than during summer) until 5pm, which is the time with the highest number of rides.  

In summary, summer peak times are 8am, and 2pm to 8pm while fall/winter peak times are 8am, and 1pm to 7pm.
The change in evening peak time in December is attributable to earlier sunset, which is characteristic of the winter season. 

#### Busiest Days of the Week
Zooming out into days of the week:
In September, the most popular morning start time of the week is 8am on Fridays and the most popular evening start time of the week is 5pm on Wednesdays. In December, the most popular morning start time of the week is 8am on Thursdays and the most popular evening start time of the week is 3pm on Saturdays.

#### Station Popularity
The most popular start and end stations are within the borough of Manhattan (which coincidentally has an almost equal male to female population ratio (2018 Census)). The least popular start stations are clustered with other less popular start stations. It may be more cost efficient to close some of these less popular start stations as they have less than 10 checked bikes per month.

### Recommendations/Conclusion
Based on the foregoing, I propose the following recommendations:
The program should implement increased marketing/promotional strategies to combat the decline in ridership numbers in the late fall/winter season.
Increased availability of support staff during peak hours to improve user experience.
There are a lot of stations with significantly low monthly activity. The program will benefit from optimization strategies such as terminating operations where there are two or more stations within certain proximity threshold (to be determined).
