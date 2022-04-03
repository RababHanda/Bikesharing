# Bikesharing

## Overview of Project
This project builds a business proposal for a bike sharing program based on New York City's Citibike August 2019 data. 

### Purpose

**Analytical:** The project analyzes the profitability of the launching such a program in a NYC, based on busisiest locations, peak hours and gender breakdown.

**Technical:** The project employs Tableau Public & Tableau Desktop


## Results

Please view the Tableau story [here](https://public.tableau.com/views/Challenge14_16485082943620/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)

#### 1. August 2019 Peak Hours

![image1](/Resources/august_peak_hours.png)

The above visual shows the total number of bikes checkout during each hour of the day through the entire month of August. 8:00 am - 10:00 are the busiest hours in the mornings and 5:00 pm to 7:00 pm in the Evenings.

#### 2. Top Starting Locations

![image2](/Resources/top_startting_locations.png)

The large-dark bubbles on the above map depict the busisiest areas in all of New York City through the day, while the lighter, smaller bubbles depict the opposite. This visual combined with the previous, tells us which areas must have bikes stocked at what times to meet customer needs

#### 3. Checkout Times for Users

![image3](/Resources/checkout_times_for_users.png)

The above graph shows the duration of time bikes are checked out for users. No user checks out a bike for over an hour. Most users check out bikes for around 10ish minutes (see the peak in the plot), while the maximum time users have signed their bikes out for is 50 minutes

#### 4. Checkout Times by Gender

![image4](/Resources/checkout_times_by_gender.png)

The above graph provides more insight to graph visual 3. It dipict the breakdown of checkout durations of bikes per gender. 

* Males comprise of the majority users, followed by females, followed by unkowns
* Most males checkout bikes for about 10 minutes
* Most females checkout bikes for about 10 minutes

#### 5. Trips by Weekday per Hour

![image5](/Resources/trips_by_weekday_per_hour.png)

The above heatmap shows the distribution of the number of trips made each day across the hours of the day. As seen the first bar graph, the most trips are made beetn the hours of 8:00 am to 10:00 am and 5:00 pm to 7:00 pm.
* On weekdays most trips are made on Thursdays, followed by Monday and Tuesday
* On weekends, the hours between 12:00 noon - 5:00 pm are equally busy, with Saturday being busier than Sunday

#### 6. User Trips by Gender by Weekday

![image6](/Resources/user_trips_by_gender_per_weekday.png)

This heatmap shows the usage split among genders and types of customers. As seen in graoh 2, most users are male, followed by females and the unknown. 
* No unknown gender users are subscribers
* For male subscribers, as seen in visual above, most trips are made on Thursdays, followed by Monday & Tuesday
* Trips for female subscribers are equally distributed throughout the week, with a slight slump on Wednesdays
* Unknown gender users make most trips over the weekends
* Non subscribed customers take most of their trips over the weekends


#### 7. Trips by Gender (Weekday per Hour)

![image7](/Resources/trips_by_gender_weekday_per_hour.png)

This heatmap combines visuals 5 and 6. As mentioned in above analyses, most trips are taken by males, then females and then unknown. The split through the weekdays (Thursday as the busiest, followed by Monday and Tuesday) is also reflected in this map. 

## Summary

Besides the ones alreayd presented in the story, there are many more visualizations that can be created with the data provided to give more insightgul information about the biking program. For eg:

1. Plot birth year against genders to understand which genders from which agegroup are using the bikes often.

2. On a symbol map, markers can be added for trip duration in minutes (adding code to group minutes at 5 minute intervals) filtered by color and size. This will give insights as to which stations are not going to have bikes for a certain period. This will help company purchase resources as needed and stock the stations accordingly