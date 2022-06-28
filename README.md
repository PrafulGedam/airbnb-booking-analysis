## Airbnb_Bookings_Analysis - Praful Gedam
### EDA for Airbnb Bookings Analysis

#### Index
1.Installation

2.Dataset

3.Project Motivation

4.Data Preparation

5.File Descriptions

6.Conclusion

### Installation
For Airbnb_NYC_2019, the most important library is Python along side we need some other library like numpy, pandas, seaborn and matplotlib. It is necessaryto install all packages for analysis and building models.

#### Dataset
Airbnb dataset contains data on listings with a huge number of features, user's reviews and calendar info for Airbnb homes.

#### Motivation
The reason behind choosing this dataset are:

1.How well can we predict a listing's price and what features correlate well with the pricing?

2.Where to invest in a property in Boston to get the maximum number of returns from Airbnb?

3.How well can we predict reviews and what aspects are correlated with the reviews?

#### Data Preparation
In this dataset, there are 48895 entries and 16 features (Columns )

10 out of 16 are numeric: ['id', 'host_id', 'latitude', 'longitude', price, 'number_of_reviews' 'reviews_per_month', 'calculated_host_listings_count', 'availability_365' ]

6 out of 16 are categorical: [ 'name', 'host_name', 'neighbourhood_group' 'neighbourhood','room_type','minimum_nights', 'last_review']

#### Handling Null values:
Columns like reviews_per_month has 10052 missing value or can say that null values. It is very important feature for data analysis. On other hand columns like name, last review also has missing values but we can drop it from dataset

#### Lokking for outliers
### Conclusion
The people who prefer to stay in Entire home or Apartment they are going to stay bit longer in that particular Neighbourhood only.

The people who prefer to stay in Private room they won't stay longer as compared to Home or Apartment.

Most people prefer to pay less price.

If there are more number of Reviews for particular Neighbourhood group that means that place is a tourist place.

We put good use of our latitude and longitude columns and used to create a geographical heatmap color-coded by the price of listings.

Except for Manhattan, in all the neighbourhood groups, 'Entire home/apt' is the room type that gets most traffic.

We can conclude that throughout NewYork city there is a larger preference towards Entire apt as compared to private or shared rooms irrespective to the prices hence the Traffic there are most.
