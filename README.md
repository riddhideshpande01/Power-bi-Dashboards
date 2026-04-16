1.Title: 
Airbnb globel performance dashboard

2.Description: 
The Airbnb Global Dashboard is a simple and interactive project that helps us understand Airbnb data in an easy way. It shows information like Listing accourding to the rooms, market shares by cities, ratings, trust factors, Seasonality, top reviewers, and user activity. With the help of visuals, we can quickly find patterns and compare different locations. This dashboard is created using Power BI to make the data clear, useful, and easy to understand.

3. Tech-stack: 
The dashboard was built using the following tools and technologies:
1.Power BI Desktop: Main data visualization platforms used for report creation.
2.Power Query: Data Transformation and cleaning layer for reshaping and preparing the data.
3.DAX (Data Analysis Expression): Used for calculated measures, dynamic visuals and conditional logic.
4.Data modeling: Relationships established among the tables (Listing, Reviews) to enable cross-filtering and aggrigation.
5.File format: .pbix for development and .png for dashboard preview

4.Data Source: 
Source: Maven 
Airbnb data for over 250k listing in 10 major cities, including information about hosts,pricing,location, and room type, along with over 5 million historical reviews.

5.Features: 
1.Buisness problem: Airbnb Global Performance
2.Goal of the Dashboard: The business problem behind Airbnb Global Performance is to understand how the platform is performing across different cities and countries. Airbnb needs to identify which locations have high demand, who the most active users are, and how listings and reviews are distributed.

3.Key Visuals: 
a) KPIs:  This are used in dashboards to show the most important information in a simple and clear way. They help users quickly understand performance and make better decisions without analyzing too much data.
In this dashboard KPI's are used to show the total number of Listings, total cities, total hosts and property types.
Also in the Review page this KPI's used to show the trust factor based on the profile picture and identity verification. 

b) Line chart: A line chart is used to show how data changes over time. It helps in identifying trends, patterns, and growth or decline in values easily. It is commonly used for tracking performance over a period.
Here in the dashboard line chart used to analyze the historical data of airbnb where we analyze the overall performance over a period.

c) Line and Stack column chart: A Line and Stacked Column Chart combines both bar and line visuals to show different types of data together. The stacked columns display the breakdown of values i.e No superhost and superhost while the line shows the overall trend here we use cumulutive percentage over the time.
this visual is used to show the market share by the cities 

d) Stack bar chart: A Stacked Bar Chart is used to compare total values across different categories
hence it is used in dashboard to show the average pricing as per the type of rooms like(hotel,entire,shared,private). Also in the Reviews page it used to show the top Reviewers and from which city they belong.

e) BookMarks: bookmarks help users quickly switch between different views in this dashboard bookmarks are used to switch between detailed ratings of the cities and overall ratings of the cities which help to understand which city has highest/lowest ratings makes navigation easier and improves the overall user experience.

f) Clusterd column chart: used to show the overall ratings as per the cities in the dashboard.

g) matrix column chart: used to show the detailed ratings as per the cities in the dashboard.

h) Ribbon chart: It used for easily see which category is performing best and how positions shift across different periods. 
In this dashboard this chart is used to see Month-wise, which city dominates the review share.

4.Impact & Insights: 
a) Year wise high and low number of listing and COVID-19 pandemic impact of it.
   highest number of listing: In year 2015 
   Restrain: In the year 2016-2017
   again profitable: second half of 2016
   growth stopped: from year 2018 and in year 2019 by the COVID-19 pandemic

b) Which cities are best rated and worst rated with reasons
   Best Rated cities: Mexico City and Rio are the overall best rated cities
   Worst Rated cities: HK and Istanbul due to cleanliness and value for money ratio is lowest

c) Average pricing per cities as per the room types like(hotel room, entire place, shared room, private room)
 Paris, NYC and Sydney account for almost half of total listing and 48% of total reviews.
 Paris having most listing and reviews because of prices of hotel rooms.

d) Trust Factor 
   66.9% Airbnb hosts are fully verified 
   only 0.3% hosts keeping anonymous profile 
   32.6% provide atleast one trust signal(Profile picture/identity verification)

e) Top Reviewers
   The top 5 reviewer belongs to Bangkok, Mexico City, Sydney. 
   The topo 1 reviewer belongs to Bangkok 

f) Seasonality 
   Due to European summer travel Paris and Rome dominate review share from April to August.
   New York review share increases in November and December during holidays season.
   
 Screen Shots of the Dashboard:
 overview: https://github.com/riddhideshpande01/Power-bi-Dashboards/blob/main/overview.png
 Ratings: https://github.com/riddhideshpande01/Power-bi-Dashboards/blob/main/ratings.png
 Reviews:https://github.com/riddhideshpande01/Power-bi-Dashboards/blob/main/reviews.png
