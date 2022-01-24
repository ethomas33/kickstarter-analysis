# Kickstarting with Excel

## Overview of Project
This analysis is being used to show how Kickstarter events focusing on theather / plays have faired over time. 
 
### Purpose
This analysis specifically focused on looking at events by launch month and then by initial fundraising goal.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For this analysis the first steps were to get the data set up properly - dates in usable formats (converting them as well as simiplifying to year) and the category column split up into more granular columns. This table was then used to create a pivot table to show successful, failed, and canceled Theater events by the month in which the Kickstarter was launched. This was then turned into a pivot chart to visualize the results more clearly.
 
![Outcomes Based on Launch Date](C:\Users\ethomas33\Desktop\Class\Module1\Numberofeventsbymonth.png)


### Analysis of Outcomes Based on Goals

For this analysis once the excel file structure was set up to accomidate the goal dollar levels and values the first step was determining the CountIFS formula needed to get the exact subset of the data we were looking for for each field. This was then replicated and adjusted for each of the needed cells changing values and outcomes for all events coded as plays. From there totals were calculated for each goal dollar level and percentages calculated. These values were then translated into a basic excel line chart to visualize the final dataset.  
  
![Outcomes Based on Goals](C:\Users\ethomas33\Desktop\Class\Module1\Numberofeventsbymonth.png)

### Challenges and Difficulties Encountered

Very early in the challenge I realized that the file I had been working with from the module wasn't going to work for me because it had become unorganized in a fragmented manor. Instead of trying to salvage this file I decided to start from scratch. My mental schema up to this point in my career with excel has largely been to create a subset of the data in a new sheet i.e. in this instance I would have created a new scheet of theather events only because that was all we were concerned with. This preconvieved mentality resulted in the biggest challenge of the project, I was unable to figure out why my Outcomes Based on Goals graph wasn't matching as it should to the final product and it turns out I had initially overlooked the criteria to filter for plays only in my formula.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   The conclusions you can draw from this analysis are that while events that fail are relatively consistent through out the year there seems to be a spike in sucessful events that occur in May and a sharp decline that occurs in December. 
   
- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
