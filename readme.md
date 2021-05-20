# Ford GoBike System Data Exploration

## Dataset

The data consists of information regarding 183,412 individual rides made during febraury 2019 in a bike-sharing system covering the greater San Francisco Bay area. The dataset consists of 16 features (columns) for rides started from or ended at about 329 stations.



## Summary of Findings

In the exploration, I found that 95% of the data have average tripe time less than 26 minutes, 99% with average trip time less than 53 minutes. While in general the average trip time is about 12 minutes. We still have some extreme values in column (duration_min) but moving forward we focus only with rows that have average trip time less than 60m.
Most of our users are subscribers 86.36%, Customer's user segement is 9.03%.  Most of the system users are Males 71.15%, Female riders represents 22.25% of the dataset.

At trips frequency level, weekends (Saturday, Sundays) have the lowest shares every week. The heghist rate happens during both Morning (7-9 AM) and evening (3-7 PM) rush hours rush hours.

99% of the system users are under age 65. The trip duration has a relationship with user's age, most of high trip duration are found for users between age range 20-60. Female users tend to have higher average trip duration time for both subscribers and customers.


## Key Insights for Presentation

For the presentation, I focus on the insights dreived from both univariate, and multivariate exploration. leave out data loading and preperation steps. Also some sections to understand the dataset are dropped from the presentation. 
The presentation is organized as follows:
1- Preprocessing: Understanding the shape of the dataset
2- Univariate Analysis: Analysis cover the following attributes (Trip Duration in seconds and Minutes, Distribution of User Types, User gender distribution, Temporal analysis and When are most trips taken in terms of time of day, day of the week, and User Age).
3- Bi-Variate / Multivariate Analysis: Shows the influence of stations, member age, user type, and member gender on the average trip time. 

