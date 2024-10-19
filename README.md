# Project-1
Visualizing student survey data

The purpose of this project/study has been to look at student surveys that were administered to students enrolled in any computer classes at ccm. My topics of interest were as follows:
  1. For those who want to take more computing classes, what is the distribution of which classes they wish to take.
  2. What percent of those who only took a computer class as a requirement want to take another computer class.
  3. What is the distribution of which classes they wish to take.
  4. The distribution of 'some impact' and 'high impact' for the question 'To what extent did the following activities or experience impact your decision to enroll in a computing course at CCM?'

For this project we had 4 data files from non-majors. Each data file was from a given year starting with 2020 and ending with 2024. The data files were then combined into one large data file "final_df" consisting of
776 entries. Depending on the question, either only the final_df file was used or the question was asked for each year.

For the first question I decided to create bar charts for every year as I was curious to see how the interest level has changed over times as it can be indiccative of student's interest in computing over time. 
I believe this was the right decision as if we compare the chart from 2020 to 2024, we can see that less students answered a 1 (not interested) and more answered a 5 (very interesting) in the year 2024. That 
implies that more students are interested in computer classes. I also created a bar chart for all the years, but found that 2021 was an outlier so I excluded it. I believe this is a good benchmark to compare the 
past years or previous years too. If interest levels are bellow or above this chart, we can presume that it's a new trend.

The second question was similar to the first, but this time it only focused on students who were not that interested in computer classes to begin with. I believe this data exploration is more significant than the first one
as we can visualise how engaging the classes are. I also excluded 2021 as the data was an outlier. I found this data quite interesting, while in the first question most people answered a "3", when we looked at students who
took a computing class because it was a requirement, we find that "3" has less of a peak and the students that would have answered with a "3" instead were distributed among the other ranks. The not so surprising find was
that those who took the class as a requirement were not as interested in taking another class as those who took the class for other reasons.

Next, we looked at which classes students wanted to take. I actually found the findings surprising. Due to my own bias, I was expecting machine learning to be one of the most popular classes, however it was dead last.
The winner was Game Design which is really unsurprising considering this is young men we're talking about. I was also surprised that CyberSecurity came in second. The most surprising thing of all was how evenly distributed 
class interest was.

Lastly, we looked at what experiences were the most likely to create interest level in computing classes. Previous school computing class was the most significant considering those that have taken a computer class in the past
would be more likely to take more, as the interest already existed. This can be useful information as ccm can use this to create or market their computer classes to high schoolers in computer classes. I was surprised to see
that teacher counselors rated so highly as well, that could yet be another avenue for increasing the size of computing students. This implies that the best tactic for ccm to use is focus on High Schools.
