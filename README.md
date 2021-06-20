# Kickstarting with Excel

## Overview of Project
 Louise is a playwright looking to start her own fundraising campaign to help fund her play “Fever”. Being a little reluctant and despite her budget of over $10K, Louise first seeks out analytical expertise to pin point specific reasons a campaign’s outcome would be successful. For the initial analysis to Louise, some important observations were made. First, while there are a total of 4144 Kickstarter campaigns across 19 countries, the theater category is the most popular at 1393 campaigns. The theater category is also the most successful at 839 out of 2185 successful outcomes (exhibit A). The play subcategory follows a similar trend; out of three subcategories (i.e. musical, plays, spaces), plays are in lead with a total ot 1066 campaigns compared to 187 for spaces and 140 for musicals. As like the theater category, the plays subcategory also has the highest number of successful campaigns at 694 out of 839 (exhibit B). 

![alt tag](https://github.com/elrvra/kickstarter-analysis/blob/main/Exhibit_A_Parent_Category_Outcomes.png)
![alt tag](https://github.com/elrvra/kickstarter-analysis/blob/main/Exhibit_B_Subcategory_Outcomes.png)

 When analyzing the outcomes based on launch date for all campaigns categories, there was a spike of successful campaigns that began in May and then tapered off by the end of the year (exhibit C). By comparison, the technology campaigns reveals a different story. Instead of one large spike, their trend lines are all over the place (exhibit D). Furthermore, when creating an area chart of play outcomes based on active days, there is another large spike, reflecting a whopping 239 successful play campaigns and where those campaigns are active for 30 days (exhibit E). 

![alt tag](https://github.com/elrvra/kickstarter-analysis/blob/main/Exhibit_C_D_Theater_Technology_Outcomes_Based_On_Launch_Date.png)
![alt tag](https://github.com/elrvra/kickstarter-analysis/blob/main/Exhibit_E_Play_Outcomes_Based_On_Active_Days.png)

 In conclusion, it seems that Louise will a good chance at having a successful campaign given the popularity and success rate for plays. It is also looks like May is a good time for Louise to begin her campaign, but it is good to keep in mind that the length of a campaign is correlated with its success, so it should not run too long.
 
 Now, in order to further her understanding of the campaign arena, Louise would like to see how other campaigns compare to one another, by looking specificcally at their launch dates and their funding outcomes which can be summarizedd below.

### Purpose
 The purpose of this project is to deliver an analysis of Kickstarter Campaign data by use of pivots, graphs, and formulas to display pertinent details that will help Louise plan her campaign timeline as well as gauge the goal ranges needed in order to be successful in her campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
When creating a line chart to visualize the relationship between outcomes and launch month, it can be observed that there are specific months when funraising campaigns do better. The highest month for successful theater outcomes was in May at 111, followed by June and July at 100 and 87 respectively. Therefore we could assume that it is easier to throw a campaign during these months prompted by a higher frequency of funding activity. 

![alt tag](https://github.com/elrvra/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
When creating a line chart to visualize the relationship between percentage of outcomes and goal amount ranges, it can be observed that there are more people who give a smaller donation of <$5000, with 388 successful campaigns receiving goal amounts in the range of $1000-$4999 and 141 successful campaigns receiving goal amounts less than $1000. These amounts make up the majority at 76%. Therefore, we could assume that funders cannot support a higher amount or that funders may need to give lower amounts due to the many fudraising campaigns one could give to.

![alt tag](https://github.com/elrvra/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One of the challenges encountered, was interpreting the data into a meaningful analysis that tells the story of what is happening with the numbers. It is easy to get lost in the numbers and over analyze every detail assuming everything is pertinent to the story, but this was overcome by me understanding the goal and purpose of the story, and then then me asking questions to point my focus on where I need to analyze and compare to achieve it (e.g., is there a time plays are more successful during the year, how long are campaigns active for, what is the success rate for plays, what is the average donation for successful plays).

Another challenge I encountered was understanding the chart information. For me, its easier to look at numbers on a screen and decipher what is high or low, what period is significant or not, etc. Playing around with the different chart options help me overcome this challenge and better enable me understand what is happening and what chart best expresses the data clearly from an analytical standpoint and so that it is in line with the feedback I need to provide to achieve the goal and purpose of the research. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Based on my analysis, successful theater outcomes peak in the month of May making it a good time of year to start a fundraising campaign, as they begin to taper off for the rest of year. This may indicate that funders are more active during this time of year; although this is global data, it is possible most campaigns launched in May are experiencing the summer season
2. Based on my analysis, successful theater outcomes and failed theater outcomes are almost the same for the month of December. This may indicate that it is more difficult to throw a fundraising campaign during this time of year as compared to the warmer months, due to it being flu season and people are less active.

- What can you conclude about the Outcomes based on Goals?
1. Plays with a goal amount of <$5000, have the highest percentage of successful outcomes so it is a good idea when initiating a funraising campaign to review the goal amount ranges by id before seeking funding. This could indicate that most people do not have the ability from a financial standpoint to give any other amounts out of this range. It could also suggest, that one or more donors could be giving out multiple donations during any given year, and the amounts given in this range satisfies donating to most or all of those committments.

- What are some limitations of this dataset?
1. The dataset does not show how long successful theater outcomes are active for, which seems to be a contributing factor.
2. The dataset is not by year, which could alter the highs/lows of the data points as well as the and goal amount ranges for a successful campaign.

- What are some other possible tables and/or graphs that we could create?
1. Average donation by month of successful play outcomes.
2. Active days (i.e. launch date minus start date) of successful play outcomes.
3. Amount of backers by country of successful play outcomes.
4. A clustered column chart can be used in stead of a line chart for theater outcomes by launch date.
5. An area chart can be used instead of a line chart for outcomes based on goals. 