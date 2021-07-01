# Kickstarting with Excel

## Overview of Project

	An analysis of a Kickstarter campaign with an express focus on outcomes based on funding goals and earnings. The provided data is from a crowdfunding campaign of various types of theatre shows.

### Purpose

	A simulated analysis based on a client wanting to know the relation between launch dates and funding goals compared to the funding outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
	
	To show the relation between outcomes and launch dates, data taken from the Kickstarter campaign was organized based on the month the funding goal succeeded, failed, or was canceled. The data was then visualized using a line graph to better show the results.

 



### Analysis of Outcomes Based on Goals

	To show the relation between outcomes and the funding goal, data was orginized based on the expected goal amount and the amount of succeeded, failed, and canceled projects. The data was then visualized in a line graph.

 



### Challenges and Difficulties Encountered

	One challenge that came up during the Kickstarter analysis was trying to have the date only show up as months instead of a full date. For example, making the date show up from "Day, Month, # of day, Year" to just "Month" was a challenge as this is my first time working with Excel. 
	The solution was to use an "=IFS()" function to have the numerical month date be changed into a text format by using multiple if statements to have a number between 1-12 to each month of the year.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	
	Two conclusions that can be drawn from the Outcomes based on Launch Date is that there was a rise in sucessful projects around June, July, and August with the peak of success being in July while the most failed projects were on October and August with relatively similar amounts of failed projects.

- What can you conclude about the Outcomes based on Goals?

	Based on the Outcomes based on Goals, we can conclude that there is an equal percentage of success and failure for projects with a goal of 1000 to 4999 with around a 30 precent success/failure rate.

- What are some limitations of this dataset?
	
	Some limitations of this dataset is that there is no data for what region in each country were the pledges being made and cannot allow us to see if there are any specific citys or states where the projects had the most interest and no data for age demographics to better focus advertising for future projects.

- What are some other possible tables and/or graphs that we could create?

	Some possible tables and/or graphs that could be created are how many projects were successful or failed in each country and what categories succeeded or failed to show a possible trend for popularity of a certain category in each country.

