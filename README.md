# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis was to evaluate outcomes of Kickstarter campaigns across the world. Different variables were used to evaluate outcomes, such as filtering by different types of campaigns, the goal amount, the country, or the launch date. Campaigns could be differentiated by whether they were successful, canceled, failed, or live. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analyze outcomes based on launch date, a pivot table was created showing the outcomes of theater campaigns (i.e., successful, failed, canceled) across each month of the year. The filters included the category and years, the legend included the outcomes, the axis was the launch data, and the values included the outcomes.

### Analysis of Outcomes Based on Goals
To analyze the outcomes based on goals, the COUNTIFS() function was used in Excel. This function was used to calculate the outcome of campaigns by taking the goal amount filtered by the outcome (i.e., successful, failed, canceled) only for campaigns in the play subcategory.

### Challenges and Difficulties Encountered
I originally selected the wrong columns the first time I used the COUNTIFS() function and was not selecting the goal column as one of the criteria. As my graph did not match what was shown in the module, I continued to replay the example video until I identified the error. Once I the goal amount was set as one of the criteria, then I added the outcome column as another, ending with the specified subcategory. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The month of May had the highest number of successful theater campaigns that were launched. In general, theater campaigns launched in the summer months were more successful than theater campaigns launched during other seasons. Theater campaigns launched during December and January were least successful.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98051208/151814903-78cac176-4ef8-40b9-82c0-00c7abb05d4e.png)



- What can you conclude about the Outcomes based on Goals?
The outcomes of play campaigns were most successful when the goal was between $45,000-$50,000 or between $25,000-$34,999. Roughly half of the play campaigns with goals outside of these ranges failed.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98051208/151814934-6c198c8b-3e2c-45af-9ed3-0bb5973981eb.png)


- What are some limitations of this dataset?
One limitation of the current dataset is it does not include all Kickstarter campaign data. Another limitation is the data are not being updated, any campaign categorized as “live” has likely since ended. Additionally, other influential factors to the success or failure of the campaign, such as who shared the launch of the campaign and how it was described, are not included in this dataset. These factors would be harder to quantify, however, public opinion data and responses could be coded as positive or negative. Also, the platform used to announce the launch may also be useful to include in the analysis.

- What are some other possible tables and/or graphs that we could create?
Additional ways the data could be analyzed could be evaluating each category on its own and analyzing the outcomes of each subcategory within that parent category. This information may be useful to someone who has a general idea of a campaign they would like to launch, knowing which subcategories are more likely to be successful would help. It would also be interesting to view outcomes across countries, to see if certain types of campaigns are more likely to be successful in different areas of the world. It would also be useful to evaluate outcomes not only by the goal amount, but also by the number of backers. 
