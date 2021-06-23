# Kickstarting with Excel

## Overview of Project
### Purpose

The purpose of this project is to analyze the theather campaigns launch dates and plays funding goals for a better understanding of their relationship with the campaing outcome. This analysis is based on KickStarter data set using observations from many countries to obtain data driven insights reported in this project. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date


To start this analysis once the Creation Date was converted from UNIX format to a readable format date the Excel YEAR() function extracts the launch date year which was useful for filtering outcome counts by month. Then an Excel pivot table was created to visualize a theather campaigns outcomes by launch date month using the observations from KickStarter dataset.

Below chart visually displays the outcomes trend by month, the peak of succesful campaigns were in May and in December the likelihood of success vs fail is almost even. 

![image_name](path/to/image_name.png)


### Analysis of Outcomes Based on Goals


Using goal ranges the theather-plays campaigns were counted and classified based on outcome to calculate the percentage of each one. Excel COUNTIFS() functioned allowed to perform counts based on multiple condition criteria to cluster campaign goals vs outcomes. Then based on percentages successful campaigns and failed campaigns trends were identified for each goal range.

The following line chart visually displays the outcomes trend by month, the peak of succesful campaigns were in May and in December the likelihood of success vs fail is almost even. 


![image_name](path/to/image_name.png)

### Challenges and Difficulties Encountered


## Results


- What are two conclusions you can draw about the Outcomes based on Launch Date?

*A theather campaign launch in May, June or July will most likely succeed
*A December Launch has a high likelihood of failing, less than 50% of chance to succeed therefore would be 
*the worst month for launching a theather campaign 

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

statistically might not be relevant to state that are successful 

- What are some other possible tables and/or graphs that we could create?
**Recommendations for the analysis would be to create, visualize and analyze: **
*Launch Date and goals Outcome charts being filterable by country, so the analysis can show market preferences and trends.
*Determine ranges of Beckers/Pledge rates to identify how it would influence the campaign outcome
*A Stacked Bar Chart for Spotlight vs Outcome

### Analysis Reference
Underlying data, tables and charts used for this analysis can be on below Excel workbook link:

[filename](path/to/filename.xlxs)

