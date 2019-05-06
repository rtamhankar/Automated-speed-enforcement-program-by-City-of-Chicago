## Insight 1
### Automatic Speed Enforcement Program effective?

First Visualization "Impact of Automated Speed Enforcement Program: Violations decreasing as more number of cameras are deployed over the years?" shows how the number of violations are reducing over the years with increase in the number of cameras. As more number of cameras are deployed from the years 2015 to 2018,the number of violations are decreasing. The trend line indicates that number of violations are further likely to reduce in 2019 by implementing more number of cameras. It can be concluded that the decrease in the speed violations is a result of Automatic Speed Enforcement program. Hence, the Automatic Speed Enforcement program should be continued in future as the decrease in the speed violations would result in reducing the vehicle crashes/accidents. The line graph clearly represents the trend in the number of violations over the years as the number of speed violation cameras are increased.
Revisions done:
1. Running total for the number of cameras has been added and shown with the help of a line graph.
2. Trend line has been added for both count of cameras and sum of speed violations.
3. The years 2014 and 2019 are excluded as the data for the entire year is not available for these years.
4. Grid lines have been removed.

While showing the decrease in the total violations over the year, I thought, if I show the percentage decrease for each quarter within a year, it would effectively portray the efficiency of the program. Hence, I was curious to know the trend of violations throughout the different quarters over the years. I chose the line graph for this visualization as well, as I could clearly portray the core message by plotting years and quarters on X-axis and violations on Y-axis.
In the second visualization, the trend of violations throughout the different quarters over the years is shown. A very interesting finding from the visualization is that the percentage of violations is decreasing for all quarters except for the quarter2(Q2). If we consider Q2 of the years 2015,2016,2017 and,2018 we can clearly see that there is an increase in the % violations as compared to the previous quarter. As far as 2014 and 2019 are concerned, there is no data available for Q2-2014 as the program was launched in Q3-2014 and Q2-2019 has just the data till current date. Hence,2014 and 2019 are not considered in this visualization. The quarter wise trend in the violations convey the message that appropriate measures should be taken for reducing the number of violations in Quarter 2. Can the violations be monitored for the current Q2-2019 quarter to find out the root causes of sudden surge in the speed violations in Q2?
Revisions done:
1. Color wise distinction for each quarter instead of representing all the quarters within the same year with same color.
2. The years 2014 and 2019 are excluded as the data for the entire year is not        available for these years.
3. Grid lines have been removed.
4. % sign has been added when showing the percentage change for a quarter with respect to the previous quarter.

#### Visualizations

1.[Insight1_Viz1](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight1_Viz1.JPG)

2.[Insight1_Viz2](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight1_Viz2.JPG)

 3.[Insight1_Story](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight1_Story.JPG)

#### Conclusion

The Speed Camera violation program seems very effective as there is a decrease in number of violations with increase in the number of cameras over the years from 2015 to 2018. Appropriate measures should be taken to reduce the number of violations in Quarter 2.


## Insight 2
### Can the redundant cameras be removed?

First visualization "Top 'N' Camera Ids with maximum violations" represents the camera wise number of violations in the descending order of violations captured by each camera. It represents the contribution of each camera in the total violations. The bar chart clearly shows the comparison between the violations captured by each camera. The interactive feature of the visualization allows the observer to select Top 'N' camera ids from the range 5 to 20.The camera Ids at the bottom of visualization seem to capture very less violations. There can be two scenarios.
1.	The cameras need to be checked if they are working properly.
2.	Once it is confirmed that they are working properly, it can be assumed that there are minimal violations in those areas and people follow the speed limit rules in those areas.
Hence, those cameras can be considered as redundant and they can be deployed in the regions with more number of violations.
Revisions done:
1. Interactive feature has been added to allow the user to select Top 'N' camera Ids.
2. Grid lines have been removed.

To show the redundant cameras effectively, the cameras with less than total 1500 violations over the years are shown. The second visualization conveys the actual number of violations captured by these cameras in the text table format. The visualization format is very easy to understand as there are less number of rows. The community area names are also added to the text table in order to identify the community areas from where the cameras can be removed.
Revisions done:
1. The camera IDs are arranged in ascending order of sum of violations.
2. A new column to show the community area name has been added.

#### Visualizations

1.[Insight2_Viz1](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight2_Viz1.JPG)

2.[Insight2_Viz2](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight2_Viz2.JPG)

3.[Insight2_Story](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight2_Story.JPG)

#### Conclusion

The cameras with less than 1500 total violations captured so far have been highlighted so that appropriate measures can be taken to deploy them in the areas with more number of violations.

## Insight 3
### Exceptionally maximum violations within a single zip code?

In the first visualization, Zip code wise total violations are shown with the help of a bar chart. It is observed that the number of violations are exceptionally maximum for one zip code. The zip codes are plotted on X-axis in the descending order of sum of violations. The sum of violations is plotted on Y-axis. The total count of cameras mounted within the zip code are also shown.
Revisions done:
1. Grid lines have been removed.
2. Zip codes have been arranged in the decreasing order of sum of violations.
3. Count of camera ids for each zip code has been included in the tooltip.

After plotting this graph, further analysis has been done to find out the community areas associated with this zip codes. Hence, the second visualization is based on the number of violations pertaining to community areas within a single zip code. As there are only 4 community areas, they have been shown with the help of 'Packed bubbles chart' along with the additional details like community area code, community area names and number of violations.
By highlighting those community areas, we can suggest that the appropriate measures should be taken to reduce the number of violations in those areas. Increasing the fine for speeding ticket can be one of the solutions. If the fine is increased in those areas, people may become more careful to drive within the speed limit. This would definitely reduce the number of crashes/accidents in those areas.
Revisions done:
1. Single color has been used instead of using a separate color for each community area.
The shades of the single color varies depending upon the sum of violations within the community area.
2. Boolean variable appearing in the bubble chart has been removed.


#### Visualizations

1.[Insight3_Viz1](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight3_Viz1.JPG)

2.[Insight3_Viz2](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight3_Viz2.JPG)

3.[Insight3_Story](https://github.com/rtamhankar/Automated-speed-enforcement-program-by-City-of-Chicago/blob/master/Revised%20Visualization%20images/Rev_Insight3_Story.JPG)

#### Conclusion

The community areas associated with the zip code with maximum number of violations have been highlighted so that steps can be taken to reduce the speed violations in the area.

## Tableau Public Link
[Tableau Public Link](https://public.tableau.com/profile/rujuta.tamhankar#!/vizhome/Automated_Speed_Enforcement_Program_By_City_Of_Chicago/Decreaseintheviolationsovertheyears)

## References
1.[Dataset](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/gncf-3xbx)

2.[Community area names](https://www.chicagotribune.com/chi-community-areas-htmlstory.html)
