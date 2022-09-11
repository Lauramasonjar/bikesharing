# NYC Citi Bike Program

## Project Overview
### Purpose

For this project we are creating data visualization with Tableau for a bike sharing program in New York City. The idea is to analyze the data, observe the mechanics of the business and figure out how the bike share business works in NYC. This is the first step of expanding the idea to other cities. With the help of a strong and clear story along with good examples of data, we can create a proposal on how the business could work in other cities, as well.

**The Tableau story of the NY CitiBike link:** [NYC Citi Bike Story](https://public.tableau.com/views/NYCCitiBikeStory_16629226189190/NYCCitiBikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


### Background 

- Tableau is a data visualization tool which provides pictorial and graphical representations of data. 
- It allows the user to create stories that are visually appealing and understandable to any non-technical user.
- It provides a tool to create powerful analytic dashboards and tells a clear story that can be easily shared with others.
- It is simple and requires little coding or written queries as a 'Calculated Field’, to ensure your data is showing correct analytics.

## Requirements

- Change Trip Duration to a Datetime Format
  - Pandas to convert integer to a datetime datatype.
  
- Create Visualizations for the Trip Analysis
    - Tableau to create visualizations, dashboard, and story.


## Resources 
-	Data Source:
    - [CitiBike Trip History Data from August 2019 in NYC](https://www.citibikenyc.com/system-data)
    
-	Software:
    - Tableau Public 2021.4
   
-	Languages & Environment:
    - Pandas, Python 3.7


## Results

### 1. Basic Information

This is the first page of the story which is the dashboard. It contains basic information about the data set and gives details of the kind of data we will be dealing with in the further analysis. 
  
![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Basic_Information.png)

The page contains the following information:
-	Type of business (Citi Bike), location with the particular time frame of the data (New York City, August 2019).
-	Number of the total rides: 2,344,224.
-	Customer type: subscribers and customers.
-	Peak hours, divided by gender which shows the user behavior.
#
### 2. Checkout Times for Users

![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Checkout_Times_for_Users.png)

 
- This visualization shows the length of time for every bike ride during the month of August in 2019. 
- It shows that riders typically like to ride between 2 minutes and 15 minutes.

#
### 3. Check Out Time by Gender

![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Checkout_Times_by_Gender.png)


- The graph shows the number of checked out bikes and the trip duration.
- Three different colors represent the classification of gender. Orange represents male, blue represents female and red represents the unknown gender. 
- This visualization shows the breakdown of riders by gender and the duration of ride times showing that most of the users are men.
 
#
### 4. Trips by Weekday per Hour

![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Trips_by_Weekday_per_Hour.png)


- The graph shows the number of trips per hour and per weekday. 
- The graph displays the hours as rows and weekdays as columns.
- The color indicates the number of trips.
  - Darker shade color indicates more trips,
  - Lighter shade color indicates less trips.
-  From the graph we can see that the busiest times are: weekday mornings from 6am to 9am, weekday evenings from 5pm to 7pm and weekends (Saturday and Sunday) in the middle of the day from 10am to 6pm.

#
### 5. Trips by Gender (Weekday per Hour)

![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Trips_by_Gender(Weekday_per_Hour).png)

- The graph shows the number of trips per hour and per weekday. 
- The graph displays the hours on the rows and weekdays on the columns.
-  The color indicates the number of the trips.
   - Darker shade color indicates more trips,
   - Lighter shade color indicates less trips.
-  Additionally, the graph is divided by gender (male, female and unknown). 
-  From the graph we can see that distribution of the checkout times for all genders is similar.
  - The busiest times are
     - In the morning hours on weekdays from 6am to 9am
     - In the evening hours on weekdays from 5pm to 7pm 
     - On weekends (Saturday and Sunday) the busiest times are in the middle of the day from 10am to 6pm
-  However, males have significantly higher number of trips than female or unknown gender. 

#
### 6. User Trips by Gender by Weekday
![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/User_Trips_by_Gender_by_Weekday.png)

- The graph shows the number of trips by weekday, by user type (subscribers and customers) and by gender. 
- The graph displays weekdays and usertype as rows and gender as columns.
- Among subscribers, male has the highest number of trips, especially on Thursdays and Fridays, followed by trips on Monday and Tuesdays.
- Female has similar distribution of trips, with significantly lower number of trips than male.
- Unknown gender has uniform distribution of the trips throughout the week. 
- Looking at the customers data we can see significantly less trips throughout all genders with a slight increase among unknown gender on Saturdays and Sundays.

#
### 7. Top Starting Locations & Top Ending Locations

![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Top_Starting_Locations.png)
![bikesharing](https://github.com/Lauramasonjar/bikesharing/blob/main/Images/Top_Ending_Locations.png)

- With the help of these two graphs we can see the most popular starting and ending locations.
-  The bubble shapes represent the number of trips. 
  - Larger bubbles represent locations with the highest number of trips, 
  - Smaller bubbles represent lowest number of trips.
-  Downtown area is much more popular than other areas, yet it is as important for surrounding areas to have bike services for good customer experience.


## Summary

In the NYC Citi Bike story, it tells us more about the number of users and how they use the bikes per hour, by weekday per hour, who the most popular user type is, popular areas and peak hours by gender. 

**1.Bike maintenance**

- Bike maintenance plays a big role in the bike share business.
- Heat maps tell us a clear story about the data which will help us to visualize the data. 
- From the graphs *Peak Hours per Gender*, *Trips by Weekday per Hour* and *Trips by Gender(Weekday per Hour)* we can see that the least busy time is between 11pm and 5am which suggests that this would be a good time for bike maintenance.
- With the help of the data in *Top Starting Stations* and *Top Ending Stations* we can make a plan for maintenance and the rotation of bikes from a popular station to a less popular station. 

**2.Trip duration**

- The most popular trip duration checkout time is between 3-8 hours. This provides more information about the users behavior.
- There should be some flexibility on usage of bikes per mile. 

#
 
The NYC Citi Bike story says a lot about users and their trips which will definitely be helpful for us to create a Citi Bike program in De Moines. 

We should concentrate on some areas to make Citi Bike more popular and efficient for users.  

- Marketing and Advertising will play a crucial role in making Citi Bike more popular. 
- Bike stands must be easily accessible to the users.
- Bike stands should be positioned in the most crowded (as per the population) areas.
- Offering attractive rental plans according to seasons and festivals will be beneficial to the programs success.
- Considering kids as a type for some areas in the city will increase the chance of popularity among families.
