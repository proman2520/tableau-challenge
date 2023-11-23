## Tableau Analysis

The Tableau CitiBikes story consists of two dashboards that focus on different aspects of the data: the location and the time.

The data primarily centers on August 2013, however it occasionally cross-references the data with August 2019 and September 2023 as well, to see how the data matured over time.

In the first dashboard, one can see a map that illustrates the popularity of the stations by size, as well as a bar chart of the most popular stations and the number of rides by station over different intervals. Interestingly enough, the most popular stations in all three different time periods were different. There was overlap, but the most popular stations changed. This could be because Manhattan traffic patterns change, or this could be because of something else that was noticed by the number of rides graph: between 2013 and 2023, the number of stations substantially grew. There are many more stations existing in the 2023 dataset than in the 2013 dataset. Additionally, although it depends on your awareness of Manhattan geography, unsurprisingly the most popular stations bunch up around the Time Square, Central Park, and Wall Street areas. The map is overlaid on a map background of the zip codes.

In the second dashboard, one can see the rides dissected by time. There is a hourly cycle across the month of August 2013 that shows the daily rise and fall in bike rides, the aggregated trips by hour, and the trip durations, which were binned by 100 seconds. The CitiBikes were popular around 8AM, when many are commuting to work, but then peaked between 5PM and 6PM, when people are desperate to get home after leaving work. The rideshare vehicles were least popular at 4AM, which is intuitive. Regarding the trip duration, the most common duration was around 400 seconds (6.67 minutes). The graph is normally distributed around the 400 second mark. From the month graph of the hourly cycle, we can see that the pattern is typical and predictable.

Satisfying the assignment requirements in Tableau was at times frustrating and difficult, but it is understood why Tableau is a powerful tool for visualization. The dataset had serious limitations given the incongruent metrics across time, but with enough creative vision, interesting conclusions from the data can be illustrated.

Thank you for the time and consideration grading the assignment. I might add that this repository was fuller, with the three datasets and a jupyter notebook, but GitHub kept timing out while I tried to commit. I suspected it might be from the large size of the files and had to remove the .csv files that I used.

~Andrew