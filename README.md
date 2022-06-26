# Bikesharing
Project using Pandas, Jupyter Notebook, and Tableau to convert data and create visualizations for a bikesharing start-up.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Resources](#resources)
* [Results](#results)
* [Summary](#summary)

## Overview of Project
I created visualizations in Tableau using CSV data for NYC Citibike to show investors for a start-up bikesharing program in Des Moines, IA called DM BikeShare. Data is sex-aggregated and includes usertypes (subscriber, customer).

### Resources
- Data source: [201908-citibike-tripdata.csv](https://s3.amazonaws.com/tripdata/201808-citibike-tripdata.csv.zip)
- Tools: Python 3.7.11, Jupyter Notebook, Tableau Public 2022.1.3

## Results
My first story point shows top starting locations. I added filters for sex, usertype, and trip duration (hour) so investors can see how these start points differ between them. Overall, Manhattan seems to have the most bike usage - likely because there are more tourists there.

Subscribers                       |  Customers
:-----------------------------------:|:-----------------------------------:
![Subscribers](/Images/Subscriber_Start.png) |  ![Customers](/Images/Customer_Start.png)

- Subscribers start at a wider range of locations, mostly south of Central Park
- Customers start mostly along the Hudson River or around Central Park

I created a horizontal bar graph to show peak hours, with sex-aggregated colors and a usertype filter.

Subscribers                       |  Customers
:-----------------------------------:|:-----------------------------------:
![Subscribers](/Images/Subscriber_Peak.png) |  ![Customers](/Images/Customer_Peak.png)

- Subscribers largely use bikes between 7-9AM and 4-8pm
- Customers tend to use bikes between 10AM-8PM

Subscribers                       |  Customers
:-----------------------------------:|:-----------------------------------:
![Subscribers](/Images/Subscriber_Weekday.png) |  ![Customers](/Images/Customer_Weekday.png)

- Subscribers use bikes more often from Monday to Friday
- Customers use bikes more often on weekends

![Tripduration](/Images/Tripduration.png)

- Most users use bikes for under 30 minutes

The full Tableau story can be viewed [here](https://public.tableau.com/app/profile/nicole.white3373/viz/CitibikeStory_16562458595720/NYCCitibike).
- Males ride more bikes
- More customers than subscribers have unknown sex

## Summary
From these visualizations I would recommend that DM BikeShare presents to investors that:
- Subscribers will
  - Make the largest chunk of the user base
  - Find locations near residential areas and workplaces most convenient
  - Use bikes mostly for commuting
- Customers will
  - Find locations near tourist spots most convenient
  - Use bikes mostly on weekends/holidays
  - Be more likely to have missing sex data

Additional visualizations that should be created are top starting and stopping locations with markers for public transportation to check if there is correlation. Likely, having bike stations close to other public transport will be more convenient for users. Other data that would be good to have is the size of bikes and their fit depending on sex, perhaps bikes made for females would help the bikesharing program to increase their female user base.
