# Kickstarting With Excel

## Analyzing Kickstarter Data for Insight Into Campaign Success and Failure

### The purpose of this analysis was to help a client, Louise, gain a greater understanding of data accumulated regarding Kickstarter campaigns, so that she could move forward with her own campaign with a greater understanding of how to succeed in her efforts.  In this analysis, we looked specifically at data regarding *launch dates* and *fundraising goals.*

## Analysis and Challenges
I completed this analysis by sorting and clarifying the data to show the correlation between a campaign's success in reaching it's fundraising goal and:
- the start date of the campaign
- the stated dollar amount of the fundraising goal.

### Launch Date Analysis
To determine the relationship between the campaign's success and it's start date, I created a pivot table from the main dataset to analyze the outcome of the campaign relative to the month of the year in which it started.  I also created a chart to visualize the pivot table.  I filtered this data to specifically look at Kickstarter campaigns for theater only.  
![Launch date screenshot.PNG](C:\Users\ashle\OneDrive\Desktop\Classwork\Crowdfunding Analysis\Resources\Launch_date_screenshot.png)

### Goal Amount Analysis
To determine the relationship between a campaign's success and it's stated fundraising goal, I created a new sheet that broke down the data into amount ranges and determined the number of successes and failures of campaigns within each range. I both counted the number of each outcome per range, and then determined the percentage of each outcome based on the total number of projects in each range.  
![goals screenshot.PNG](C:\Users\ashle\OneDrive\Desktop\Classwork\Crowdfunding Analysis\Resources\goals_screenshot.png)
![Outcomes_vs_Goals.png](C:\Users\ashle\OneDrive\Desktop\Classwork\Crowdfunding Analysis\Resources\Outcome_vs_Goals.png)

### Challenges and Difficulties Encountered
A challenge for the Launch date section of the project was using a pivot table and chart, having only limited experience before this time.  After some experimentation, I was able to get the table to display the appropriate information and I was also able to format both the table and chart to look how I like in terms of colors and line weights.

A challenge for the Goal section of the analysis was using the COUNTIFS function to bring data to the new sheet from the main dataset.  I had never used this function before, and it took a few tries to really understand the syntax and to render the data correctly.  For instance, I was using ' when I should have been using ".  My final chart does not match the chart in the project example and I cannot for the life of me figure out why.  It is very close and I can only surmise that there is an error in how I rendered the data into the new sheet, but I am unable to determine the reason.  When the Kickstarter sheet is filtered to only include plays, there are no "canceled" outcomes. However when the COUNTIF function is used, it shows some 'canceled' outcomes nonetheless.  I am unsure if that is the problem, or how to fix it, since the Kickstarter sheet was filtered when I used the function.

Also my images don't work and I don't know how to make them.

## Results

### Outcomes Based on Launch Date
Two conclusions that can be drawn from the analysis of Outcomes Based on Launch Date are that campaigns that are Launched in the months of May are the most likely to be successful, with June a close second, and those launched in December are the least likely.

### Outcomes Based on Goals
Analysis of the data for success based on the amount of the fundraising goal show that small campaigns, less than $1000, show the highest percentage of success.  However, the highest number of campaigns are between $1000 and $4999, and 66% of those are also successful.  So a campaign between $0 and $4999 have the highest likelihood of success overall.

### Limitations of the Dataset
One limitation of this dataset is that the location data only provides for the country of origin.  Theater tends to be most heavily produced in large cities where there is both a larger audience for the productions and a larger pool of backers for fundraising campaigns. I would be interested to see how the data corresponds to city size.  Another limitation might be demographic information on backers of successful campaigns.  It would be useful to know if campaigns targeted to a specific age group, for example, would yield better results.  
### Additional Tables and Graphs
Within the limits of this dataset, it would be helpful to have a few additional tables or charts to clarify the data more thoroughly.  For instance, a simple bar chart of the goal ranges of successful campaigns, to succinctly clarify the success rate of smaller efforts.  Also I think a table/chart showing the outcomes of campaigns relative to the length of the campaign.  I think it likely that there is an ideal length of time needed to secure enough backers and donations.
