# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was create an analysis from Kickstarter data to visulize campaign outcomes based on their launch dates and funding goals. Louise's play Fever came close to its fundraising goal and she would like to know how the different campaigns fared in relation to their funding goals and launch dates. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A pivot table was created from the Kickstarter worksheet to isolate the each month of the year so that count of each of the outcomes either successful, failed or canceled could be tallied. The Parent Category was filtered to show only 'theater'as the criteria. A line chart was created from the pivot table to visualize the relationship between outcomes and launch month.

![Theater Outcomes vs Launch:](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
A new table was created with a column with dollar amount ranges representing the goal for each project. A COUNTIFS() function was used to calculate and populate the outcome fields such as successful, failed and canceled. The Subcategory was filtered to show only 'plays' as the criteria. The Sum() function was used to populate the totals. The percentages of the successful, failed and canceled outcomes were calculated. A line chart was created to visualize the relationship between the goal amount ranges on the x-axis and percentage of successful, failed or canceled projects on the y-axis.

![Outcomes vs Goals](resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
A challenge that came up was getting the totals to add up in the Outcomes based on Goals table. After debugging the code I found a typo and was able to correct so that everything added up correctly. I also had some challenges with creating the grouping of the Row Labels to show the months of the year. With some trial and error I was able to figure it out and display it properly.
## Results

- The two conclusions that can be drawn about the Outcomes based on Launch Date are:
    - The outcomes of Theater campaigns have a higher success outcomes in May and June
    - The outcomes of Theater campaigns have a lower success outcome in December
    
- What can you conclude about the Outcomes based on Goals?
    - That between the dollar ranges of greater than 0 and less than 5000 have the highest success outcome
    
- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

### Links
[Kickstart Challenge Excel Document](Kickstarter_Challenge.xlsx)
