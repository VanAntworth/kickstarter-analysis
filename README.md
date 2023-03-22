# Kickstarter Analysis

Performing analysis on Kickstarter data to uncover trends.

### Purpose

This excel project was created to assist Louise (an upcoming playright) in analyzing the kickstarter data to see how different campaigns fared in relation to their launch dates and their funding goals. Data analysis on several thousand crowdfunding projects was conducted to uncover hidden trends.

Estimated a budget of $10,000

Data was collected from the past crowdfunding projects from 2009 to 2017, in various categories as theater,food,music etc. 
By analyzing this data I will assist Louise in finding insights as to how the various campaigns fared in relation to their funding goals, launch dates etc. For this purpose I am using MS Excel and will build my analysis using pivot charts and tables, conditional formatting, VLOOKUP, CountIFs and other excel formulas.


## Analysis and Challenges

Visualize campaign outcomes based on their launch dates and their funding goals. I first took time to review and understand data presented. 

<img width="953" alt="Tabular Data" src="https://user-images.githubusercontent.com/99001393/155908842-09d3f315-ae62-4232-bb71-9485c3dcd50f.png">

### Analysis of Outcomes Based on Launch Date


To best show Louise a breakdown of correlations between Launch Date and successful Theater campaigns a pivot table was created to compare outcomes by month and a line chart was made to best visualize this data.



<img width="1000" alt="Theater Outcomes Based on Launch Date" src="https://user-images.githubusercontent.com/99001393/155908883-da55628b-31a4-4744-8622-fe9072262ad1.png">



### Analysis of Outcomes Based on Goals


Overall the data shows the percentage of successful projects decreases as the goal amount increases.

There is an increase in the successful percentage between 35-45 thousand dollars but looking at the number of projects in that range shows an insignificant number of total projects. Showing more data in the chart such as the number of projects per category could provide more insight.

<img width="1415" alt="Outcomes Based on Goals" src="https://user-images.githubusercontent.com/99001393/155908866-fd84cd22-4890-4e73-a87e-d2c891969b54.png">

### Challenges and Difficulties Encountered

When creating the Outcomes Based on Goals Tab 
-To make the sumifs formulas easier to drag down I used two columns for the <> values. I then encountered a challenge using those columns to create an axis label and had to convert them back into a single text column (as shown in column J above)

## Results

- Two conclusions that can be drawn about the Outcomes based on Launch Date 

The month that launched the most successful Kickstarter campaigns was May. The failures per month seem to be unchanging therefore the launch date of a campaign does not make a differnece in the number of failures.

- What can you conclude about the Outcomes based on Goals?


Based on the Breakdown of the goal amounts in the sheet the majority of successful campaigns had goals of lower that $10,000 therefore
you can conclude that lower the Goal amount the higher rate of success.

- What are some limitations of this dataset?

The line chart we provided does not show number of projects in each goal category. If you were only referencing the chart you would see an increase in the successful percentage in the 35-45 thousand range but looking at the total number of projects in this range shows there is an insignificant amount of data points in this range.


- What are some other possible tables and/or graphs that we could create?

Adding a bar chart on top of the percentage line chart (showing the number of projects in each goal range) would provide more insight.

<img width="1028" alt="Overlapping Bar Graph" src="https://user-images.githubusercontent.com/99001393/155924629-09fbf99e-3ddb-4118-a2f9-36c14c5d5208.png">


