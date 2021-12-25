#Kickstarting with Excel

##Overview of Project

###Purpose 
The purpose of this analysis is to determine how the outcome of a Kickstarter fundraiser relates to the goal and timing of the fundraiser. This analysis will be essential to help Louise launch a succesful fundraiser on Kickstarter for her new play "Fever".

##Analysis and Challenges

###Analysis of Outcomes Based on Launch Date 
Using Kickstarter data from 2010-2017 I created a pivot table and line chart to be able to cleanly filter and visualize the data based on the month of launch date. The filter I applied was "theater" to get a more accurate representation of the data for Louise's "Fever".
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96211484/147371352-5c4f2528-05ca-43fa-b157-8d53bfd4c3d9.png)

###Analysis of Outcomes Based on Goals
The second analysis I did was the outcome of the fundraiser based on the fundraising goal. To accomplish this, I used the COUNTIFS() function to pull the number of successful, failed, and canceled fundraisers within 12 different fundraiser goal ranges, within the subcategory "Plays". I created a line chart based on the percentage of successful, failed, and canceled fundraisers.![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96211484/147371583-3da5b361-6613-4287-8e2d-e69a616dff50.png)


###Challenges and Difficulties Encountered

##Results Two conclusions I can draw from Theater Outcomes by Launch Date is that May, June, and July clearly had the most succesful Launch Dates, while May and October had the most failed. What does this mean? I think an interesting angle to take would be to look at the percentage of successful, failed, and canceled fundraisers based on Launch Date like we did with Outcomes Based on Goals. There were the most, exactly 166, "theater" campaigns launched in May so naturally there would be more successful and failed fundraisers in that month.

One conclusion to make from Outcomes based on Goals is there was a VERY steep drop off in success rate for any goal over $44999. Goal range $45000 to $49999 has a 0% success rate (although only one sample) and fundraiser goal > $50000 has a 13% success rate (16 sample size). It appears essential to keep the fundraising goal tame and realistic.

A limitation of the data set is I think more data could be mined from "backers_count". It would be possible to find the average pledged based on backer just by dividing "pledged" by "backers_count", but average only tells one side of the story. More information about the backers would be essential, would help identify outliers, and could really help explain where the money is coming from and why.

Further analysis to run would be what I mentioned in ##Results while talking about Theater Outcomes by Launch Date. A table that shows the percentage of Outcomes based on Launch Date would give a better visual as to what months are optimal to launch a Kickstarter campaign in.
