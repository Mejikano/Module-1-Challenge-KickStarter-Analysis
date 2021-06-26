# Kickstarting with Excel

## Overview of Project
### Purpose

The purpose of this project is to analyze the theather campaigns launch dates and plays funding goals for a better understanding of their relationship with the campaings outcome. This analysis is based on KickStarter data set using observations from many countries to obtain data driven insights reported in this project. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date


To start this analysis once the Creation Date was converted from UNIX format to a readable format date the Excel YEAR() function extracts the launch date year which was useful for filtering outcome counts by year. Then an Excel pivot table was created to visualize a theather campaigns outcomes by launch date month using the observations from KickStarter dataset.

Below chart visually displays the outcomes trend by month, the peak of succesful campaigns were in May but in December the likelihood of success vs fail is almost even. 

![Theater_Outcomes_vs_Launch](https://github.com/Mejikano/Module-1-Challenge-KickStarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.PNG)


### Analysis of Outcomes Based on Goals


Using goal ranges the theather-plays campaigns were counted and classified based on outcome to calculate the percentage of each one. Excel COUNTIFS() function allowed to perform counts based on multiple condition criteria to cluster campaign goals vs outcomes. Then based on percentages successful campaigns and failed campaigns trends were identified for each goal range.

The following line chart visually displays the success and failed percentage trends by goal ranges. 

![Outcomes_vs_Goals](https://github.com/Mejikano/Module-1-Challenge-KickStarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.PNG)

### Challenges and Difficulties Encountered

One of the challenges was how to include Goal ranges into the conditional count formula; reading the documentation I decided to split into two different criteria_range and criteria for lower and upper range boundaries when intuitively I tried to factor them together as one criteria i.e. AND(>=1000, <5000).

## Results


- What are two conclusions you can draw about the Outcomes based on Launch Date?

*A theather campaign launch in May, June or July will most likely succeed
*A December Launch has a high likelihood of failing, less than 50% of chance to succeed therefore would be the worst month for launching a theather campaign 

- What can you conclude about the Outcomes based on Goals?

*A goal range between 1,000 and 4,999 tends to be successful for theather-plays campaigns 
*Plays subcategories were never cancelled regardless of the campaign goal 

- What are some limitations of this dataset?

Some outcome counts could derive biased conclusions; for instance the Outcomes based on Goals analysis suggests that Goal ranges between 35,000 and 49,000 have a 67% chance to be successful however these results are based on very few observations that statistically might not be relevant or they could even be outliers. More data might be required before jumping into that conclusion.



- What are some other possible tables and/or graphs that we could create?
**Recommendations for the analysis would be to create, visualize and analyze: **

-Launch Date and goals Outcome charts being filterable by country, so the analysis can show 
     a)Launch Date  market preferences and trends. 
     b)Goals should be significantly different for each country as average population income is very different 
     
     Therefore considering all countries data points to base the decision for the US market may skew the analysis 
        
-Determine ranges of Beckers/Pledge rates to identify how it would influence the campaign outcome
-A Stacked Bar Chart for compering Spotlight: True/False vs Outcome

### Analysis Reference
Underlying data, tables and charts used for this analysis can be found in the following zipped Excel workbook link:

[Kickstarter_Challenge](https://github.com/Mejikano/Module-1-Challenge-KickStarter-Analysis/blob/main/Kickstarter_Challenge.zip)

