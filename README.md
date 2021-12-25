# Bike-sharing 
An analysis of NYC CitiBike Data, using:
-	Tableau for Data visualization
-	Pandas and Jupyter Notebook for cleaning data.
- Find the Tableau Story for this project in this link [The Story]( https://public.tableau.com/app/profile/intisar3500/viz/NYCCitiBikeVizualizations/ChallengeNYCCiti-Bikes?publish=yes). 
## Project Overview
The purpose of this project is to analyze bikeshare data from CitiBike in New York City []() for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. This analysis conduct to through answering of some questions:

```
      •	What is the length of time that bikes are checked out for all riders and genders?
      •	What is the number of bike trips for all riders and genders for each hour of each day of the week?
      •	What is the number of bike trips for each type of user and gender for each day of the week?
```    
## Analysis and Results:
### Data Cleaning: 
1.	Using Python and Pandas functions, we converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds. After we converted the "tripduration" column to a datetime dataytpe, we exported the DataFrame as a CSV file named ```201908-citibike-new-tripdata.csv```.   
2.	Using ```Calculated Field``` to change the data type for the Gender Columns from number ```Int64``` to ```String``` and change the data labels using ```IF then statement```. 
### Create Visualizations for the Trip Analysis
1. The total Number of Trips: There was a total of ```2,344,224``` trips for the month of August. 
2. Customer Types: The pie chart show that there are ```1,900,359``` users subscribe to the company while ```443,865``` users are customers.
3. The Peak of August: The top riding hours during August in New York City  ``` 5:00 p.m to 7:00 p.m.``` during the day in August.
4. The Checkout Times for Users.The line graph of number of trips by duration show that most trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in   length, with a swift drop off in number of rides over an hour in length.
5. The Checkout Times by Gender: The line graph for breakdown of number of rides by duration, separated by gender, shows that the male customers have  many more rides than females.
6. The Trips by Weekday for Each Hour: The results in  the heatmap shows that the peak riding hours during the  weekday between ```(6-10AM and 5-8PM)```, and during the weekend usage between ```(5am to 10pm)```. 
7. The Trips by Gender (Weekday per Hour): Results in the heatmap indicates that Males are High users during the peak Hours. 
8. The User Trips by Gender by Weekday:  The heatmap indicates that male subscribers are highest users.
## Summary: 
 we can summarize the finding for this project in the following points:
 - 


