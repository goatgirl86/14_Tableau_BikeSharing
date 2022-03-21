# 14_Tableau_BikeSharing

## Relevant Folders and/or Files
-	CSV files not uploaded to GitHub due to size.  
-	NYC_CitiBike_Challenge.ipynb
-	Tableau Story: **https://public.tableau.com/views/CitiBikeChallenge_16478201998300/CitiBikeTheNewWaytoExperienceNYC?:language=en-US&:display_count=n&:origin=viz_share_link**

## Project Overview

### Purpose
The purpose of this challenge was to help “Kate” assess NYC Citi Bike data from August 2019 and then create a story in Tableau illustrating key outcomes of the NYC Citibike analysis.

### Data Analyzed
New York City Citi Bike Data (August 2019):
-	201908-citibike-tripdata.csv.zip (https://s3.amazonaws.com/tripdata/index.html)

### Deliverables 
The deliverables for this assignment were:
-	Deliverable 1: Change Trip Duration to a Datetime Format
-	Deliverable 2: Create Visualizations for the Trip Analysis
-	Deliverable 3: Create a Story and Report for the Final Presentation


## Results

### Deliverable 1
DataFrame showing conversion of tripduration column to datetime format.

![image](https://user-images.githubusercontent.com/92705556/159193179-683693ff-86fc-458e-9d19-329ed304d11d.png)


### Deliverable 2

Viz 1: Number of Rides by Trip Duration: This figure illustrates the number of rides compared to length of ride.  Most rides are 5 minutes in length.  
 
![image](https://user-images.githubusercontent.com/92705556/159193184-52c0a605-1dd8-478c-86f9-fc04eb912879.png)


Viz 2: Number of Rides by Trip Duration, split by Gender: This figure illustrates that men are the top user and their rides are predominantly 5 minutes long.
 
 ![image](https://user-images.githubusercontent.com/92705556/159193187-78b0ae74-4763-41df-a885-20affbea170a.png)


Viz 3: Trips by Hour of the Day. This figure illustrates that most rides (dark purple) are taken during the morning and evening commutes.  Saturdays have steady usage throughout the day.  

 ![image](https://user-images.githubusercontent.com/92705556/159193194-e0ac001e-5f01-4ab8-892f-9ccb63bdb74a.png)

 
Viz 4: Trips by Hour of the Day, split by Gender. This figure illustrates that most rides (green color) are taken during the morning and evening commutes and are taken by men.  

![image](https://user-images.githubusercontent.com/92705556/159193212-af6beec4-8a87-41b6-a9c3-319f8e502efb.png)

 
Viz 5: Trips by User Type, split by Gender. This figure illustrates that most rides are taken by “Subscribers” and are taken by men on Thursdays.  
 
![image](https://user-images.githubusercontent.com/92705556/159193222-fcb7f6ce-bb95-42bc-978e-27e85d83f681.png)


Viz 6: Top Starting Locations. This figure illustrates that most rides start in the Manhattan area of NYC.  This area probably has high density of jobs and is also a main tourist attraction.  

 ![image](https://user-images.githubusercontent.com/92705556/159193226-d5786417-97a3-4d4d-a4ef-67e65e4fd5cd.png)


Viz 7: Usage by Bike Id. This figure illustrates the individual bikes with the most and fewest rides.  Bikes that are ridden more often will likely need more attention and repair. 
 
 ![image](https://user-images.githubusercontent.com/92705556/159193232-e8030035-88cc-472f-ac1c-b73f5e483b34.png)


Viz 8: Rides by Birth Year. This figure illustrates the number of rides by birth year that can be extrapolated to say “number of rides by age”.  You can see there is a huge spike in ridership of individuals born around 1970 (50 year olds) and around 1990 (30 year olds).
 
 ![image](https://user-images.githubusercontent.com/92705556/159193238-e9bf08a8-733e-43d3-8021-d09e5394f9ff.png)

 
Viz 9: Rides by Station Name. This graph shows all the station names and the number of "start rides" from those stations. This info could be helpful to determine where more bikes should be added or which stations may not be worth the cost of upkeep.

 
![image](https://user-images.githubusercontent.com/92705556/159193239-5879299a-8e38-4373-82ff-62a98bd47cb0.png)


## Summary
### Conclusion
Citi Bike NYC is a fruitful business seeing lots of ridership.  
- Men were the primary user in 2019 with most of them taking short rides around 5 minutes in length.  
- Most rides took place in Manhattan where there is a high density of jobs and many tourist attractions.  
- Citi Bike should consider individual bike usage when prioritizing repairs.  
- Citi Bike may also consider doing some additional targeted advertising that will encourage increased ridership by women.  

### Future Analysis
I actually already completed two additional analyses on my own (see Viz 8 and Viz 9 above).  Viz 8 shows ridership by birth year (to determine what age of riders are the greatest users).  Viz 9 shows ridership by station name (to determine which stations need more bikes vs which ones may need to be closed).  


