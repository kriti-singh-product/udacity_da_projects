# FordBike dataset exploration and insights
## by Kriti Singh


## Dataset

> This dataset consists of 1863721 rows and 14 columns and has been integrated by concatenating monthly databases of ford bikes for the year 2018. The dataset consists of variables like duration, start station name, end station name, start station id, end station id, latitudes, longitudes, user type, bike share etc. The data was extracted from https://s3.amazonaws.com/baywheels-data/index.html


## Summary of Findings

> The dataset obtained from the above link was concatenated into a single csv. Then I segregated the start time column into various columns such as start time day, start time weekday, start time hour and start time month. The visualizations plotted from analysis made were:
Univariate:
1 A histogram plot for the duration of bike rides and maximum bike rides were for 500-700 seconds.
2 The second plot was the bar plot of monthly bike rides.
3 The third plot was the pie plot for weekly bike rides.
4 The last univariate plot that was plotted was the one containing histogram for hourly bike rides.
Bivariate:
1 Bivariate plots show relationship between two variables and the first graph plotted is the violin plot for start time hour vs start time weekday.
2 The second graph plotted shows the relation between the start time for the bike rides taking place with sharing status i.e there are bike riders who share bikes and some don't.
3 The pie graph plotted in the third section shows the customer and subscriber percentage.
4 The last bivariate plot gives a plot for the average duration for each weekday.
Multivariate:
The multivariate graph plotted here gives the relationship between duration and bike share for all weekdays.


## Key Insights for Presentation

> From the above visualizations the main insights I have observed are as follows:
1 Average duration of rides is 500-700 secs.
2 Maximum rides take place from May-Oct.
3 There are more number of bike rides on weekdays than on weekends.
4 On an average riders who do not share bikes start early than who share bikes.
5 There are approx 85% subscribers and 15% customers in the dataset.
6 The bikers who do not share bikes travel for the longest durations on the weekends.