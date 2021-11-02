# Tableau_challenge

The task was to aggregate data found in the Citi Bike Trip History Logs and find two unexpected phenomena. Then design 2-5 visualisations for each phenomena, plus two dashboards and a map. 

The two phenomena that were looked at are following: 
    1.	Viewing the differed in member and casual users plus preferences in type of bike. (Eg Classic, Docket or Electric). 
    2.  Finding out the top performing stations to start and end a journy. In addition, breaking down user activity by month, hour and weekdays to see if there’s any clear patterns. 

Steps Undertaken: 
    Step 1: Visted the City Bike website to download all the csvs from February to September 2021. (Please note that recent changes to the format of the dataset limited the range of the data I could use.) 

    Step 2: Uploaded the data to Tableau creating a union between all the files to makes it easier to work with. (Main reason I choose to limit the data set to recent months) 

    Step 3: Started looking at the first phenomena choose a pie chart as it illustrates best the two different types of user group (member vs casual).

    Step 4: Looking at types of available bikes with three different types classic , docket and electric, plotted a simple bar graph and placed member type as break down to show with user group prefers what type of bike. 

    Step 5: Started looking at the top stations to start and end a journey plotted a few bar graphs, but decides a table illustrating the top ten values for both was much more clear as some values where close making it hard to see the difference. 

    Step 6: Line graph that shows all the top ten start station performances over the period of the data set. Used the ‘start at’ sorted by month as column and count of ‘feb.cvs’ total number of values as rows. Filtered by ‘start station names’ set to the top ten stations. 

    Step 7: This chart looks at the top ten stations breaking down activity by the hour, using ‘Started at’ column sorted to hours and count of ‘feb21.csv’ total number of values in the data set as the rows. In the filters section used ‘start station name ‘and ‘start at’ sorted to month allow the user to view the break down over per hour activity for the stations. 

    Step 8: Looking at the data monthly breakdown by weekdays. The aim was to see if there was a pattern of days people used the bikes. Used ‘start at’ sorted to weekday and count of start lat as rows. Filtered the data using start at sorted by month. 

    Step 9: Wanted to see more information about activity at the most popular station so built a similar chart to step 7 but limited it to E 17 st & Broadway. This allowed better understanding on activity on the stations. This showed almost identical demand in the morning with less correlation in the evenings. 

    Step 10: To make the map converted the geographical data related to start stations to dimension’s used start latitude and start longitude as column and rows. Filtered by start station names and placed the ‘feb21.csv’count as the size and color as the name. To make the map cleaner added a page filter where people can filter by month reduces the data on the map easier to read. 

    Step 11:  To make the map converted the geographical data related to end stations to dimension’s used end latitude and end longitude as column and rows. Filtered by end station names and placed the ‘feb21.csv’count as the size and color as the name. To make the map cleaner added a page filter where people can filter by month reduces the data on the map easier to read. 
    Step 12: Created a Top stations Dashboard 
    Step 12: Created a story (using below descriptions) 

***I WOULD LIKE TO POINT OUT THAT THE WRITE UPS WERE DONE BEFORE UPLOADING THE WORKBOOK DUE TO RESTRICTION I HAD TO REDUCED THE FINAL DATA SET.  YOU CAN FIND COPY FULL VERSION ON GITHUB. ****

*** IMAGES OF FULL CHARTS LISTED BELOW ***

Story Write ups for each graph: 

Intro page: 
    Viewing the post Covid19 recovery for New York City and the City Bike program. Using data collected from February to September to view changes in demand over the period. 

Page 3 Membership and bike types. 
    Understanding our membership breakdown which illustrated on the pie chart shows us 67.19% member riders vs 32.81% Casual riders. Furthermore, riders who have a casual pass choose classic bikes over docked ones. 

Page 4 top ten stations tables. 
    The most popular station to start and end a journey was E17 street & Broadway. Out of the 10 stations 9 appear in both categories. Outlining the popularity of city bikes in the central areas of New York. 

Page 5 Line chart Monthly Break Down. 
    Viewing the performance of the top 10 stations to start from it shows sharp upwards trend in user numbers. This fits in line with Office workers and public being allowed to return to the city. The trend pikes in June and there’s a drop in users until August. 

Page 6 Line chart Hourly break down by Month. 
    Breaking the activity data into hours the top ten stations see similar activity in context of time of day with a sharp increase from 5 to 10 in the morning and piking at 4 to 6 in the evenings. Notable that 1 Ave & Est 68 street sees significant user demand compared to other users both in the mornings 5234 and evenings 10 762 users overall, showing a significant demand for services in that area. 

Page 7 line chart Station bike demand by month. 
    Analyzing the top performing station over the last 9 months shows how demand has increase with each month. Although demand starts of at around 5 -6 in the morning with sharp increase apart from February, March and April where numbers aren’t as strong. User demand shows pikes in the morning around 9- 10 and there’s a uptrend until 17 to 18 in the evening.  

Page 8 
    The chart shows you ride users broken down to days and months, first three months of the year Tuesday and Wednesday’s popular days during the week and Saturday as the most popular day during the weekend. Although recent months data shows no common points its worth mentioning drop in users on Friday and Sundays. 
