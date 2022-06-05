# Kickstarting with Excel

## Overview of Project

### Purpose
This project is to examine theater kickstarters in the kickstarter campaigns data to evalaute and visual the sucsess, failure or cancelation of the campaigns' outcome based on launch date and estiamted funding goal. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
As seen in the Theater_Outcomes_vs_Launch Chart, the majority of successful campaigns in the theater category were launched in May and gradually declined in success as the months' progressed. Failed campaigns have a fairly steady trend throughout the year, spiking in May and October. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105950742/172063456-192dbade-5df4-4b1b-9245-31fe5fc6adbf.png)

### Analysis of Outcomes Based on Goals
As seen in the Outcome vs. Goals Chart, plays that have larger funding goals tend to fail in comparison to plays with smaller funding. Although there is a spike in successful plays in the high range of 35,000 to 44,999, there is also a greater percentage of failure. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105950742/172064552-267a60bf-d282-41c4-82b3-79c33fe8def8.png)

### Challenges and Difficulties Encountered

#### Challenges of Outcomes Based on Launch Date
The challenges for this analysis are ensuring your Pivot Table fields contain the correct fields in the correct quadrant. The field where I experienced the issues was the "Rows" quadrant. It is imperative to pay attention to the "Date Created Conversion" field options vs. the "Date Ended Conversion column." As this analysis is for the launch date, the "Date Created Conversion" is the field needing to be analyzed. Please note if you use the Date Ended Conversion column, it will give you the same grand total summations, but the datapoint within the table will be incorrect. 

#### Challenges of Outcomes Based on Goals

The challenges on this data set are ensuring the proper formatting of the formula for excel, in particular, paying attention to criteria have proper punctuation, i.e ",< and columns are correct. 
  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

It is recommended to start a campaign in March or April. May has the most successful Campaigns but steadily declines as the months go on. If the campaign is started before, it has a high probability of reaching its goal before the decline and not be overlooked with the increased campaigns.

Viewing the overall data and seeing trends for the previous three years, campaigns have a high probability of failing when started in the latter part of the year, around September to December. 

- What can you conclude about the Outcomes based on Goals?

There is a higher probability of a sucessful campaign with a smaller funding goal. 

- What are some limitations of this dataset?

Taking into account the location of the campaign is an important fact. Depending on location, there can be different trends in when backers are willing to give money and how much a backer can donate. 

Outcome-based on Goal could also benefit in taking time launch date into account. Knowing how long it takes for the funding to be accomplished. 


- What are some other possible tables and/or graphs that we could create?
I would alter the Pivot Table for the Theater Launch Date to account for Country. I would also perform a whisker and box plot for Outcomes based on Goals to see what the outliers are. 
