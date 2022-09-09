# Citi Bike Business Analysis

## Purpose
- The purpose of this project is to demonstrate skills using Tableau and analyzing bike sharing data. 
- Visualizations were created using Tableau to pursuade potential business investors to open a bike sharing company in Des Moines, Iowa. 

## Project Overview
- Bike sharing data is transformed into interactive visualizations using Tableau. 
- Multiple graphs and maps are created to show multiple aspects of a successful bike sharing company. 
- Graphs in Tableau have filters for users to select times, genders, areas where bike sharing data is most relevant to them. 


### Challenge Overview
- The data type for the trip duration in the original data set is converted to a datetime data type using Pandas and Jupyter notebook. This allows for better analysis and visualizations in Tableau. 
- Multiple charts and maps are created to show busy times for bike utilization based on day of the week and gender. 
- The Tableau worksheets are then organized into a Tableau story with narration. 

## Results
**1. Checkout times for all users can be filtered based on the time of day. The line chart shows that bikes are most frequently checked out during the morning and evening commutes.**
![image](https://user-images.githubusercontent.com/104038813/189180077-031077b6-dd3d-4ae6-8c71-72bf34de51fd.png)

**2. The same checkout chart can also be filtered by gender and by hour of the day. Based on this chart, men use the bikes more often, but the times for men and women appear to be similar.**
![image](https://user-images.githubusercontent.com/104038813/189180647-b81d9343-533f-4fd7-829b-ee38bae94b03.png)

**3. The gender breakdown shows that men make up roughly 65% of all users. Women make up 25% and the rest of the users did not put a gender down when they registered for the bike.**
![image](https://user-images.githubusercontent.com/104038813/189180942-f79aba7e-8979-40b3-93fc-77bc609a946c.png)

**4. The users were categorized by whether they had signed up for a monthly subscription or not. Subscribers used the bikes more often and made up 81% of all users.**
![image](https://user-images.githubusercontent.com/104038813/189181422-8505b7e2-030c-4df2-a48c-09e63bed307c.png)

**5. The most common times that the bikes were used was during commuting times in the morning and afternoons. Weekends saw more usage during the middle of the day.** 
![image](https://user-images.githubusercontent.com/104038813/189181612-210fbbb4-ae61-4593-ad2f-b72079893f08.png)

**6. The day and time of bike usage can be broken down by gender. Both men and women show similar patterns on the busiest times to ride bikes.**
![image](https://user-images.githubusercontent.com/104038813/189182155-a12a7c69-8458-4c62-9557-a5e4dbdb10d2.png)

**7. The bike sharing business is directed towards any specific generation or age range either. People of all ages rely on bicyles as a main form of transportation.**
![image](https://user-images.githubusercontent.com/104038813/189182364-e8568b71-2f48-4642-9518-57f8caadc4a2.png)

**8. The company can track which bikes get used the most, where they are used, and which ones will need maintenance.**
![image](https://user-images.githubusercontent.com/104038813/189182511-160808b4-b843-4b88-905d-85690c00bc6c.png)

## Summary
#### A bike sharing business in Des Moines, Iowa would be very profitable. Heres why...

1. Bike sharing data in New York City shows that a majority of bike users are utilizing the bike as a form of transportation to and from work. People in Des Moines will also have to commute to work. 
2. People of all ages ride bikes, because people of all ages need transformation to work or school. 
3. Weekend usage is during the middle of day when tourists are active and visiting a variety of downtown sites.
4. Men and women both utilize the bike sharing opportunity, even though men do use the bikes more often. 
5. Trips were taken to reach a destination, but also to return them back to where they started, usually later in they day. 

**Finally, since people in Des Moines travel for work and visit downtown sites, a bike sharing business would be successful.**

### Additional Visualizations
- A chart showing total trips with respect to population in that area would give insight into how many bike rides per person there were. This would be helpful since the population sizes of New York and Des Moines vary drastically. 
- A chart showing start and stop locations compared to the number of attractions in the area would give insight into the reason why people are biking to a particular location. The chart could have bubbles or circles with the radius represented by the number of attractions in the area.

## Resources
- Data Source: 201908-citibike-tripdata.csv, converted citibike_data.csv
- Software:  Tableau Public, Pandas, Jupyter notebook
- MSU Bootcamp Spot Module 14: https://courses.bootcampspot.com/courses/2508/pages/14-dot-0-4-citi-bike-cruisin?module_item_id=636896
- **Link to Tableau Public source:** https://public.tableau.com/views/CitiBike_Challenge_16626520469680/NYCCitiBikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

