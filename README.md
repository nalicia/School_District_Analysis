# School_District_Analysis
Analyzing school data using Python
## Overview 
This week my task was to aid Maria in analyzing Standerdized Test scores for the schools in the district. We needed to test the data for insights on performance, identify trends and come up with a strategic solution to solve the question of how much funding each school will recieve the following year. As we were finishing up the school board supervisor notified maria that the csv file we used to complete the analysis showed academic dishonesty. In turn we needed to take out the corrupted data so that our analysis would be fair and honest. We needed to replace the math and reading scores of the ninth graders attending Thomas High Shool. Keeping the other data intact I replaces the reading and math scores with NaN. The last step was redoing the district analysis to see how the changes affected the overall analysis. 
## Results
The percentage of Thomas High SChools' overall passing in the district summary DataFrame skyrocketed from 65% to 90%. Likewise the reading and math averages, as well as reading and math percentages for Thomas High School increased as well. 

Removing the ninth grade scores from Thomas High School proved that the average reading and math scores of the 10th, 11th, and 12th graders were ~relitviley high. 
INSERT
They were ranked in the top 5 schools. 
INSERT\
The schools who recieved more money per student had the lowest scores. 
Based on the data the smaller schools (ranging from <1000 students to >2300 studnents) did better in reading and math than the larger schools (ranging 2000<). 
## Summary 
The school budget is largley based on how many students their are, but grades also play a factor. 
