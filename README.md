# Kickstarting with Excel

## Overview of Project: Using data from Kickstarter, we analyzed for trends that predict successful outcomes for campaigns intended to fund theatrical productions, specifically plays. 

### Purpose: Through analysis of the given Kickstarter data, we can advise on when it would be most advantageous to launch one's campaign to fund a play, and on what funding goals are likely to succeed.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date: The "Theater Outcomes Based on Launch Date" chart shows the number of successful, failed, and cancelled campaigns for Kickstarters in the "theater" category, broken down by month. Within the Excel workbook, the data can be further filtered down by year, for campaigns from 2009 through 2017, with catch groups of campaigns prior to 5/17/2009 and campaigns after 3/15/2017.
![image](https://user-images.githubusercontent.com/83254435/117589563-e294b180-b0ef-11eb-9928-f355ec57552e.png)
https://github.com/mcarson16/kickstarter-analysis/blob/a4244828ca8f2ddeda2675ddf3bec0bc1d6e6424/Theater_Outcomes_vs_Launch.PNG

### Analysis of Outcomes Based on Goals: The "Outcomes Based on Goal" chart shows the percentage of successful, failed, and cancelled campaigns for Kickstarters in the "plays" subcategory of the "theater" parent category, broken down by funding goal ranges from <$1000 to >$50,000, increasing in $5000 increments after the initial <$1000 category.
![image](https://user-images.githubusercontent.com/83254435/117589570-ec1e1980-b0ef-11eb-87ec-d7e5a667b515.png)
https://github.com/mcarson16/kickstarter-analysis/blob/a4244828ca8f2ddeda2675ddf3bec0bc1d6e6424/Outcomes_vs_Goals.PNG

### Challenges and Difficulties Encountered: IT was very important to specify exact ranges that did not overlap for the "Outcomes Based on Goal" dataset and chart. Failure to do so created redundancy in the COUNTIFS function.

## Results

### Campaigns launched in May are much more likely to succeed. The "Theater Outcomes Based on Launch Date" chart shows 111 successes in May, with 52 failures. The Summer months overall hold higher success rates, a trend that steadily diminishes through September. The least advantageous month to begin a campaign is December, where we see just 37 successful campaigns, nearly matched by 35 failures. 

### There is a significant drop off in success rates when campaign goals exceed $45,000. The ideal funding range appears to be either less than $4999, with a success rate above 70%, or between $35,000 and $44,999 with a success rate of 67%. For a full theatrical production, the latter would be a realistic goal. However, there are only 9 total projects within the $35,000 to $44,999 range, compared to the 720 total projects in the range below $4999. Additional analysis is recommended before drawing a firm conclusion.

### These analyses were not restricted by country, and the dataset did not include the option to restrict by state or geographic region in the United States. People may be more or less willing to pledge to the campaign depending on where they live, and where the play is to be produced.

### This dataset also did not include a qualitative breakdown of backer levels or the amount spent on advertising for the campaigns, factors which would likely be influential in the success or failure of individual campaigns.

### "Outcomes Based on Goal" should be further investigated within the "theater" parent category and "plays" subcategory, to better model realistic budget expectations for a full scale production.
  
### A chart that models the number of backers and average donation against the funding goal could inform desired campaign reach, and help inform plans to advertise the campaign.
