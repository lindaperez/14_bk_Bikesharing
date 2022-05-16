# Bike Sharing Business Analysis

## Overview 

Determine the viability of starting a new business of bike-sharing in Des Moines using the data from the NYC bike-sharing service. 


Main Visualizations
  * Number of rides
  * Show the length of time that bikes are checked out for all riders and genders
  * Show the number of bike trips for all riders and genders for each hour of each day of the week
  * Show the number of bike trips for each type of user and gender for each day of the week.

## Resources 

- [Citi Bike System Data page (Links to an external site.)](https://www.citibikenyc.com/system-data)
*File: 201908-citibike-tripdata.csv.zip
- [Tableau Public, Dashboard](https://public.tableau.com/app/profile/linda.perez/viz/NYC_citibike_challenge_16526601638260/DataAnalysisStory)

## Tools used

- Jupiter Notebook
- Tableau Desktop 
- Tableau Public

## Results: 

[Dashboard Tableau Link for this project](https://public.tableau.com/app/profile/linda.perez/viz/NYC_citibike_challenge_16526601638260/DataAnalysisStory)

* This Dashboard shows the top locations where the bikes are generally taken for customers to start their trips. Manhattan looks like the main place to pick up the bikes for a short/long trip.
* The number of Short-term customers and Long-term customers, 19% Customers 81% Subscribers respectively.
* The total amount of Trips 2,344,224.
* The Average trip duration by birthdate. Representing the ages of customers/subscribers who take trips shorter/longer. In general, the later the birth year, the longer the ride duration.  


![This is an image](https://github.com/lindaperez/bikesharing/blob/main/NYC%20Citi%20Bike%20Dashboard.png)

#### Checkout Times for Users Viz

The trend of the Number of Records for Tripduration Minute is broken down by Tripduration Hour. The view is filtered on Tripduration Hour, Tripduration Minute, and Number of Records. The Tripduration Hour filter keeps 0, 1, and 2 due to the majority of the trips having around 4 to 7 minutes of duration.

![This is an image](https://github.com/lindaperez/bikesharing/blob/main/checkout_times_for_users.png)

#### Checkout Times by Gender Viz

The trend of the Number of Records for Tripduration Minute is broken down by Tripduration Hour.  The color shows details about Gender Category. The view is filtered on Tripduration Hour and Gender Category. The Tripduration Hour filter keeps 0, 1, and 2. The Gender Category filter keeps FEMALE, MALE, and UNKNOWN. The average duration of every trip of the women is 6 min. Women do even shorter trips. Unknown gender generally takes between 2 and 30 minutes of trip duration.

![This is an image](https://github.com/lindaperez/bikesharing/blob/main/lengthRidersGenders.png)

#### Trips by Weekday for Each Hour Viz

Number of Records (color) broken down by Stoptime Weekday vs. Starttime Hour. The view is filtered on Starttime Hour and Stoptime Weekday. 
This view shows that the majority of the trips during the week are for commuting between the hours 7-9 am (404,000 trips) and 5-7 pm (582,000 trips). For Saturdays from 1-6pm (113,000 trips) and Sundays 10am-3pm (172,000 trips).

![This is an image](https://github.com/lindaperez/bikesharing/blob/main/bikeTripsWeekdayHour.png)

#### Trips by Gender (Weekday per Hour)

This visualization shows that the majority of the trips are done by Males between 7-9 am and 5-7pm every day except Wednesdays. 

![This is an image](https://github.com/lindaperez/bikesharing/blob/main/bikeTripsRidersGendersHour.png)

#### User Trips by Gender by Weekday Viz

This view shows  the majority of the type of users and the days where the trips are taken the most. 

![This is an image](https://github.com/lindaperez/bikesharing/blob/main/bikeTripsUserGender.png)


## Summary: 

Things that would be interesting to analysis would be:

1.- Number of locations to pick up and check out bikes by city, county and state. That would give an idea about how many centers should be created to guarantee a balanced distribution of bikes and wide accessibility. 

2.- Number of bikes per station to determine how to start with the inventory.  


