# An Analysis of Kickstarter Campaigns

## Overview

Louse is a young upcomming playwritter, who has just launched her first crowdfunding campaign to fund her play *Fever*. With our statitical analysis we helped her reach the goal  $10K USD to cover from sets and costumes to advertising and actors. She was keen on starting her first Kickstarter campaign; so se has asked our for help to determine weather there are specific factors that make a project campaign successful. 

With a set of over 4000 Kickstarter campaings we understood and, therefore, generate insights that helped Louise's campaign to come close to its funderasing goal in a short amount of time. Now she wants to know how different campaigns fared their launch dates and their funding goals.

## Analysis
At first, we sorted the data by categories to get an overview of the onew with the best outcomes; where we found out "Theater" was the most successful one:

![Parent Category Outcomes](https://user-images.githubusercontent.com/90527212/134426440-40e678ae-3292-42fe-a84d-3d677648c483.png)

### Analysis of Outcomes Based on Launch Date

We wanted to find out a relationship between seasonality an the outcome of the Theater campaings. We analyzed data from 2009 to 2017 and found out some interesting information. Over the years there is a peak of successful campaigns over the month of May, while on December both successful and failed reach almost the same point. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90527212/135378017-ab78907d-0c73-4ad9-a976-26771208b470.png)

Therefore we can say that there is an influence on the launch date that can help campaigns to reach better results. 

### Analysis of Outcomes Based on Goals

But what about the goals setted? Now we focused on the *Plays* subcategory in order to analyse the outcome based on a range of goals. From a a set of more than 1000 *Plays* campaigns, we determined 12 ranges starting from less tha $1000 USD to over $50K USD. Then we counted the campaigns for each outcome and goal range, and then calculated the percentage of each outcome between each range.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90527212/135387493-c2b1fa9c-6826-4bd8-87e6-8d8fff6e3dec.png)

This time the results didn't show a clear relationship between the goal setted and the outcome of the campaign. Therefoe there must be other factors rather than the amount pledged that can influence a campaing to succed or fail.

### Challenges and Difficulties Encountered

A challenge we faced during this analysis was paying close attention when working and repeating formulas over the same set of data; for example with *COUNTIFS()*, where even when we copy and paste the formula we still neede to change manualy the criteria or make sure to be refearing to the correct range.

## Results

When running this analysis we conclude that Launch Date does have a positive outcome when selecting the right seasonality for your campaing; around the summertime is the best time to launch a new campaign. As it is not a great time to launch a Theater campaign by the end of the year.

On the other hand we conclude that there is not a certain relationship between the outcome of the *Plays* campaigns and the goal pleaged. There must be other factors such as cualitative data that with this dataset we might not be able to measure that might influence more the outcome than just the amount pleged.




