# Kickstarting with Excel

## Overview of Project

Louise started a fundraising campaign for her play Fever. She was able to achieve her goals in a short amount of time. In this project, we will help Louise to know how different campaigns fared in relation to their launch dates and funding goals.
To help Louis, we used a campaign's outcome database that compiles information about over 4,000 campaign. Microsoft Excel was the software used to manipulate the data

### Purpose

The purpose of this project is to help Louise to know how different campaigns fared in relation to their launch dates and funding goals.
  
## Analysis and Challenges
Given the purpose of the project, we defined as relevant variable the launch date, fundraising goal, and launch date.
We analysed the outcomes of the compaing based on Launch date and based on Goals.
The Launch date analysis was exclusive to Theaters fundraising campaigns, while the Goals based analysis looked over all campaigns.

It is important to remember that this is a sample of the campaing. So, we need to use the precausions to make inference about the populations. This might be a challenge that will misguide Louise if ignored.

### Analysis of Outcomes Based on Launch Date
This analyse was performed based on the month of launch. The month we lowest campaigns being launched is December with 75 campaings. The month with more compaigns being launch is May with 166 campaings. In avarege, there were 114 campaigns launched per month. 
The month of May have the most successful campaing, a total of 111, with a success rate of 66.86%. While December is the month with the least number of successful campaing being launch, a total of 37 with a suceess rate of 49.33%.

As our data represents a sample to the countless campaigns happening around the globe, we must perform some statistic tests to correctly make inference. I created a new variable called "success rate" defined as to successful campaing launched/ total campaing lauched. This new variable allows us to compare the results of different month without being misguide by the variation of total caimpaing launch each month. Then I calculated the confidence interval (95% level of confidence) and tested if a particular month's success rate is statisticaly greater than the average. The only month with success rate statisticaly lower than the mean is the month of December.


### Analysis of Outcomes Based on Goals

This analysis aim to gain insight on how the goal amount will impact the outcome of the campaing. We noticed that for the analysed sample, the higher the goal the more unlike it is to succeed. We also notice that the higher the goal, the more likely the campaing is to be canceled. 

The results seems to be plausable, as we would expected that the difficulty to reaise more money will progressively increase (lowering the success rate).However, we must remember that not all campaigns are built and there may be other factors impacting the success rate such as a mismatch between the quality of the campaign and the amount of funds being requested. 

### Challenges and Difficulties Encountered

The challenge of this project is to understanting that we are dealing with a sample and that our finds are just descriptive statistics. 
This is a challenge because ignore that will lead us to make wrong conclusions about the dinamics of fundraising campaings. The analysis is kept at a simple level due to its purpose, which is help Louise to understant how different campaigns fared. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
That December is the worst month to launch a campaign as its success rate is below average
That in term of success rate, it doesn't really matters which month you launch the campaing as long as it is not December

- What can you conclude about the Outcomes based on Goals?

We can conclude that in general campaigns, in this sample, with larger goals had a lower success rate. 

- What are some limitations of this dataset?

There are campaign with goal in different currency, so we might incorrectly group them when we create the goals intervals.
Some campaign seems not legit, like campaign ID 2213


- What are some other possible tables and/or graphs that we could create?

We can compare success rate with:
-Duration of campaign, calculated using deadline and launch date
-Category and subcategory
-country (bar chart)
-staff pick.(bar chart)
