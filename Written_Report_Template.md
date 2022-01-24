# Kickstarting with Excel

## Overview of Project
This analysis is being used to show how Kickstarter events focusing on theater / plays have faired over time. 
 
### Purpose
This analysis specifically focused on looking at events by launch month and then by initial fundraising goal.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For this analysis the first steps were to get the data set up properly - dates in usable formats (converting them as well as simplifying to year) and the category column split up into more granular columns. This table was then used to create a pivot table to show successful, failed, and canceled Theater events by the month in which the Kickstarter was launched. This was then turned into a pivot chart to visualize the results more clearly.
 
![Outcomes Based on Launch Date](https://github.com/ethomas33/kickstarter-analysis/blob/c3e359dddcee389a10dad40c4afda9343228dcc8/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

For this analysis once the excel file structure was set up to accommodate the goal dollar levels and values the first step was determining the CountIFS formula needed to get the exact subset of the data we were looking for each field. This was then replicated and adjusted for each of the needed cells changing values and outcomes for all events coded as plays. From there totals were calculated for each goal dollar level and percentages calculated. These values were then translated into a basic excel line chart to visualize the final dataset.  
  
![Outcomes Based on Goals] (https://github.com/ethomas33/kickstarter-analysis/blob/c3e359dddcee389a10dad40c4afda9343228dcc8/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Very early in the challenge I realized that the file I had been working with from the module wasn't going to work for me because it had become unorganized in a fragmented manor. Instead of trying to salvage this file I decided to start from scratch. My mental schema up to this point in my career with excel has largely been to create a subset of the data in a new sheet i.e. in this instance I would have created a new sheet of theater events only because that was all we were concerned with. This preconceived mentality resulted in the biggest challenge of the project, I was unable to figure out why my Outcomes Based on Goals graph wasn't matching as it should to the final product, and it turns out I had initially overlooked the criteria to filter for plays only in my formula.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

   The conclusions you can draw from this analysis are that while events that fail are relatively consistent throughout the year there seems to be a spike in successful events that are launched in May and a sharp decline that occurs in December. This data implies that one should schedule their event to launch in May. It also implies that there are probably alternative reasons an event fails other than its launch date. 
   
- What can you conclude about the Outcomes based on Goals?

   This chart shows that the Kickstarter with a lower goal values seem to be more successful. 

- What are some limitations of this dataset?

	A few limitations that would need to be considered: 
		- This dataset is pretty old (pre covid) which could skew results. 
		- We are looking indiscriminately around the world. 
		- Further analysis would need to go into looking if events with given goal amounts are evenly distributed or if they are skewed. 


- What are some other possible tables and/or graphs that we could create?

	The first thing I would create is a table and graph to look at the distribution of events by value, likely stacked bar charts so you can see how many are in each of the outcomes but also the total in one view. The next thing I would create is an analysis looking at events through history not just the month in which they occurred to potentially answer questions like "is Kickstarter still an effective manner of fundraising or has the atmosphere shifted".   
