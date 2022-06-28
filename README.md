## Airbnb_Bookings_Analysis - Praful Gedam
### EDA for Airbnb Bookings Analysis

#### Index
Introduction.

2) Data Exploration.

3) Missing value Handling.

4) Exploratory Data Analysis.
Univariate Analysis.
Multivariate Analysis.

5) Conclusion.





### Introduction
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. 
This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values


### Data exploration
 There are 16 columns and 48895 rows present in dataset.
 
 This dataset has around is mix between categorical and numeric values.

 Price is a dependent column.

 Min of Price variable is 0, max is 10000$.

 Mean price is 152.72 $

 On an average people stay 7 days in a room.

 75 Percentage of times minimum nights stayed is 5.

 Mean reviews given to Room/apartment is 23.




#### Missing value handling
name’ = 16 Missing values.

 ‘host_name’ = 21 missing values.

 ‘last_review’ = 10052 missing values.

 ‘reviews_per_month’ = 10052 missing values.

 ‘name’ column we will replaced the ‘missing’ values by the use of fillna().

 ‘host_name’ will replaced the ‘missing’ values by use of fillna().




#### Exploratory Data Analysis.

![image](https://user-images.githubusercontent.com/104565229/176124430-c0897c74-e962-4cf4-839d-489818e59a1a.png)


### Conclusion
80% of the hosts are in Manhattan and Brooklyn

Sonder(NYC) and Blue ground has most number of host listings

Most of the people likes Queens and Manhattan

Even with moderate number of hosts in Queens, it generated the highest revenue out of all the neighborhood group

Most of the guests prefer cheaper price

Dona and Ji are the busiest hosts

About 90% of the guests prefer entire home/apt or private room room types.


