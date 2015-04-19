# StreetSweepingSchedule
This is a Python project which will translate the street sweeping schedule for a municipality into a calendar.  The information input is written in a text string form such as "First and Third Tuesday of the month", and must be populated on a 365-day calendar for mapping purposes.

# Objective:
I want to parse a data field in a street sweeping schedule data table.  The data field contains recurring dates in the natural language: eg. "Not Posted, Both Sides Even Month 2nd Thu" into a numerical data format for further processing in the Field Calculator.
street sweeping schedule.png
The output field that I want to create will tell me the "x number of days since street was last swept".
 
# Purpose:
I wish to statistically study whether there is a correlation between street sweeping and the coastal water quality values.  I have the water quality data in the form of on-site collected data and satellite remote sensed data, but in order to examine the correlation between these two variables, I'll need to parse the aforementioned data field with a given a "sample date".
 
## Input output:
"data sampling date (date)" + "street sweeping recurring schedule (string)" > python parsing tool > "x number of days since street was last swept (integer)"
 
