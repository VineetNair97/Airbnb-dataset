# Airbnb-dataset

## How the Airbnb’s dataset from Newyork city can help us to find the best and the economical host? ##

Airbnb, Inc. is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences. The company does not own any of the real estate listings, nor does it host events; it acts as a broker, receiving commissions from each booking. Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.
So, the intended value of this project is to get insights about the type of rooms and hosts available in NYC through visualization of various plots.

### Data Source & Preprocessing: ###
Here, I have used the data from Kaggle.com. The various features of this dataset includes name, host_id, host_name, neighborhood_group, neighborhood, room_type, price, minimum_nights, No_of_reviews, Last_review, reviews_per_month, and availability. This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.

As a part of data cleansing I implemented the following steps:
1.	In the column minimum-nights, all the values > 365 were removed
2.	In the column no-of-reviews, the reviews >500 were removed.
3.	And price>1800 and price<1 were also removed.

### Exploratory Data analysis ###

Types of neighborhood groups and their price: As it is known that Manhattan is the popular tourist spot in New York so it is quite obvious that price in that area would be high as compared to other places because the standard ofliving  is too high and the popular tourist spot and possibly people from other parts comes in here because of job opportunity finds an easy shelter through airbnb's service.


![newplot (2)](https://user-images.githubusercontent.com/53135657/72199859-226e5a80-3410-11ea-8dc3-1f092f9d5864.png)


The various room types available are either entire room or private room or the shared ones. from the pie-chart it can be seen that almost 50% of all the available room types is of entire room and just 2.5% of them contains the shared ones.
![newplot (3)](https://user-images.githubusercontent.com/53135657/72220696-56857080-3521-11ea-9a07-1355830d14d8.png)


The one Neighbourhood which stands out from the below visualization is Murray hill having the maximum average host listing counts.It is the one which is yellow in color.
![newplot (4)](https://user-images.githubusercontent.com/53135657/72220820-c7795800-3522-11ea-8786-c6fbcba19de8.png)

Of all the Airbnbs(see below) with low price there are some which stands out. Here is the listing of Top 5 Airbnbs with low price and high reviews per month.

1. Beautiful furnished private studio with backyard hosted by Melissa having the price 20 dollars
2. separate door & bathroom hosted by Modesta having the price 25 dollars
3. Private room with visit to queens #4 hosted by Sonia having the price 25 dollars
4. Happy Home 3 by Raquek having the price 13 dollars
5. Spacious 2-bedroom Apt in Heart of Greenpoint hosted by Vishanti and Jeremy having the price 10 dollars

![newplot (5)](https://user-images.githubusercontent.com/53135657/72284227-7777bf80-360e-11ea-984f-2968345156a3.png)


Manhattan has the maximum listings with the most famous one being King-Lux room in the empire city see below the plot
![newplot (8)](https://user-images.githubusercontent.com/53135657/72288861-f45b6700-3617-11ea-9d91-bb7dcbea72ce.png)

From the below plot of the Host listing counts with the host_id, It is evident that the plots yellow in color has the maximum count for listing with the host_id 30283590, has the maximum count of total 121 listings.
30283590
![newplot (6)](https://user-images.githubusercontent.com/53135657/72287424-08519980-3615-11ea-8744-8b09518c0c20.png)


The map plot shows the distribution of the various Airbnb's lsiting in the city of New-York.

![newplot (7)](https://user-images.githubusercontent.com/53135657/72287265-b3158800-3614-11ea-9e6f-0f1884da429b.png)


## Conclusion ##

This Airbnb's dataset appeared to be very rich dataset with variety of columns, that allowed us to explore various visualizations.Firstly, we have found hosts who's taking proper advantage of the Airbnb platform with maximum house listing of 121. Almost 50% of the hosts tend to rent the whole room whereas 2.5% prefer to share it with others and 46% of people tend to rent a private room which is very flexible. Since, people tend to look at reviews and ratings before taking any house the best plot of the reviews and price shows that the maximum reviewed house has the price of almost 20$/day which is quite a norm in the city of Newyork.Out of all the neighborhood Murray Hill area in the NewYork is found to have the maximum number of lisitings and most importantly out of all places in NYC, Manhattan is found to be the costiliest and has large number of houses listed for Airbnb. It is probably because of the famous tourist spot and various big companies located over there. Here's the link for the code: https://github.com/VineetNair97/Airbnb-dataset/blob/master/Airbnb_data_visuals.ipynb



