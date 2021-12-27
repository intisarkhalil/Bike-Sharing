# Bikeshare
An analysis of NYC CitiBike Data, using:
-	Tableau for Data visualization
-	Pandas and Jupyter Notebook for  Data Cleaning.
- Find the **Tableau Story** for this project in this link [The Story]( https://public.tableau.com/app/profile/intisar3500/viz/NYCCitiBikeVizualizations/ChallengeNYCCiti-Bikes?publish=yes). 
## Project Overview
The purpose of this project is to analyze bikeshare data from CitiBike in New York City []() for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. This analysis conduct to through answering of some questions:

```
      •	What is the length of time that bikes are checked out for all riders and genders?
      •	What is the number of bike trips for all riders and genders for each hour of each day of the week?
      •	What is the number of bike trips for each type of user and gender for each day of the week?
```    
## Analysis and Results:
### Data Cleaning: 
1.	Using Python and Pandas functions, we converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds. After we converted the "tripduration" column to a datetime dataytpe, we exported the DataFrame as a **CSV** file named ```201908-citibike-new-tripdata.csv```.   
2.	Using ```Calculated Field``` to change the data type for the Gender Columns from number ```Int64``` to ```String``` and change the data labels using ```IF then statement```. 
### Create Visualizations for the Trips Analysis
1. The total Number of Trips: There was a total of ```2,344,224``` trips for the month of August.

2. The bubbles in this plot show the bike utilization levels. If a bike has a higher utilization level, it will be a larger bubble.

![Screenshot (510)](https://user-images.githubusercontent.com/62036983/147428488-9d023afb-e0d0-4bcd-a4d8-ea5180b3593f.png)

3. Customer Types: The pie chart show that there are ```1,900,359``` users subscribe to the company while ```443,865``` users are customers.

![1](https://user-images.githubusercontent.com/62036983/147428590-eedc14c9-aa43-4dca-8cad-9329e4d0372a.png)

4. The Peak of August: The top riding hours during August in New York City  ``` 5:00 p.m to 7:00 p.m.``` and  we suggest bike maintenance be performed between ```2:00 a.m. to 5:00 a.m.```.

![Screenshot (516)](https://user-images.githubusercontent.com/62036983/147428569-18ceb0e2-e11a-4ffd-8a57-793eb1cdcd89.png)

5. The Checkout Times for Users: The line graph for the number of trips by duration show that most trips taken on CitiBike bikes are under an hour in length. 

![3](https://user-images.githubusercontent.com/62036983/147427198-21fec2ac-7509-4353-877d-df051c1e065b.png)

6. The Checkout Times by Gender: The line graph for breakdown of number of rides by duration, separated by gender, shows that the male customers have  many more rides than females.

![4](https://user-images.githubusercontent.com/62036983/147427220-948887b5-38ff-4e92-9c76-95a746e0a79f.png)

7. The Trips by Weekday for Each Hour: The results in  the heatmap shows that the peak riding hours during the  weekday between ```6:00-10:00a.m and 5:00-8:00p.m```, and during the weekend usage between ```5:00 a.m to 10:00 p.m```. 

![5](https://user-images.githubusercontent.com/62036983/147427248-51fced39-9ba6-4d01-b2ee-2610ad0ce0bc.png)

8. The Trips by Gender (Weekday per Hour): Results in the heatmap indicates that Males are High users during the peak Hours.

![6](https://user-images.githubusercontent.com/62036983/147427269-589f6303-75f3-4f10-afec-5bb1d2baac97.png)

9. The User Trips by Gender by Weekday:  The heatmap indicates that male subscribers are highest users.

![7](https://user-images.githubusercontent.com/62036983/147427288-4afc6413-df58-42a0-ac9a-0753745676a6.png)

## Summary: 
The bikeshare analysis for New York city data, provides a useful insights for all the project   questions regarding proof of concept, where we identifed the type and gender of the customers, the peak demand hours for service during the weekday and the weekend, and the locations   of the starting and ending of trips.   New York City is a large and densely populated city, and bikeshare service is popular, especially in places where parking is difficult. So, to clarify the vision regarding the investment in bikeshare services in the city of Des Moines, Iowa, it is necessary to provide information about the city in terms of the number of residents and their distribution within the city, the distribution of working traffic locations, and the age and gender structure of the population. It is necessary to develop visualizations to answer questions that establish the relationship between traffic’s time and locations, and the number of trips, categorized by gender and time during of the week.


