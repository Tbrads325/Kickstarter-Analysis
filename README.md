# Kickstarting with Excel

## Overview of Project

### Purpose

Following Louise's fundraising campaign she wanted to know how different campaigns did based on their launch date and funding goals. Using the same dataset from before a 
visualization for campaign results was created based on launch date and funding goals. The analysis for the Kickstarter data and these new visualizations can be seen below.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes Based on Launch Date](https://github.com/Tbrads325/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

Similar to the analysis before it appears that it is better to start a theater fundraising campaign during the months of April, May, June, and July. Outside of these months
the number of successful theater campaigns appears to fall according to the chart. However, one good thing is that no matter the month the number of successful fundraising campagins 
always exceeds both the number of failed campaigns and canceled campaigns. Thus, theater fundraising campaigns overall seem to do fairly well. 

### Analysis of Outcomes Based on Goals

![Outcomes Based on Goal](https://github.com/Tbrads325/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

Almost immediately it becomes apparent that the percentage of successful and percentage of failed fundraising campaigns for plays completely mirror each other on the chart. Moreover, a
rough explanation of this chart would be that as the goal increases the chance that a campaign is successful starts to decrease while the chance of failure starts to increase. This is 
why we see the percentage of successful campaigns slowly decrease while the percentage of failed campaigns slowly increase. The proper term being the two lines have an inverse relationship 
to one another. An interesting side note is that no fundraising campaign for a play was ever canceled at least in this dataset.

### Challenges and Difficulties Encountered

One interesting challenge within the Outcomes Based on Goal chart is that 4 campaigns with goals of 50000 were lost due to the wording of the data set. Thus, some time was spent trying to find where 
these missing campaigns had gone in the analysis. As a result is should be noted that 4 failures are missing in the "Outcomes Based on Goals" chart above. Moreover, another time consuming aspect of creating
the analysis for this chart was wording the countifs formula for each cell based on the criteria described in the goal column. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the Outcomes on Launch Date chart we can conclude that there is a good chance that a theater campaign will be successful since in each of the months the number of successful campaigns exceed the number
of failed campaigns. However, another conlusion we can make is that a campaign should not be launched in the months towards the end of the year as there are not as many successful campaigns during this time and in fact
they are almost level with the number of failed campaigns especially in the month of December. 

- What can you conclude about the Outcomes based on Goals? 

A conclusion that can be drawn about Outcomes based on Launch Date is that as the goal increases the percentage of successful fundraising campaigns will begin to decrease and vice versa
for the percentage of failed campaigns.

- What are some limitations of this dataset?

The first limitation that comes to mind is what backers the fundraising campaign is aimed towards/the demographic type of the indivuals who funded these different campaigns. If this information was known we would be able to 
figure out who to target for fundraising in the future for different campaigns based on the subcategory or parent category. Next, we have no information on the chance of success of the project/campaign. Typically, if the project has
a large chance of success it will find it easier to get funding and backing than if the project had a smaller probability of success. 

- What are some other possible tables and/or graphs that we could create?

Using a bar chart and a new column titled number of days a table and chart could be created to analyze the number of days successful campaigns took to achieve their goal. This can also be further filtered by the how much the goal is.
This would give an idea on how long a campaign might take to achieve its goal based on how large the goal is. Next, histograms can be created for successful, failed, and canceled campaigns with the bin sizes being based on goal amount so that 
we may paint a better picture of Outcome Based on Goals. 
