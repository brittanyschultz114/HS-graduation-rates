# HS-graduation-rates

Create a write-up summarizing your major findings. This should include a heading for each "question" you asked of your data, and under each heading, a short description of what you found and any relevant plots.

This project's goal was to analysize the Indiana high school graduation rate verse the waiver graduation rate. Students who attended 4 years of high school, but graduated with a waiver for meeting the state graduation requirements. We'll examine the relationships between graduation and non-waiver graduation rates; school grades; poverty rates; and school spending.

Data used in this project was gathered from https://www.census.gov/ and https://www.doe.in.gov/.

What is the differnece between the reported graduation rate and the non-waiver graduation rate?

Did you know that schools report two different graduation rates, 'graduation rate' and 'non-waiver graduation rates'. A non-waiver grauation rate is what we are typically used to seeing, the percent of students that complete all the requirments in order to get a diploma and graduate. A graduation rate means the percent of all students who 'complete' high school. They don't have to get a diploma, they can get a completeion certificate or maybe a GED. I took a random sample of schools for each year from 2015-2019. As you can see most of the time the non-waiver graduation percentage is not the same as the graduation percent. And most of the time, the non-waiver graduation percentage is significantly lower. I then took the average of graduation rates and non-waiver graduation rates for all the coporations in Indiana for each year. From 2015-2017 there is about a 5% difference in the non-waiver vs graduation rates. And then from 2018-2019 there is about a 10% difference in the non-waiver vs graduation rates. So over time we are give more waivers out and our students are not graduating with a diploma.

2019 Graduation Rate vs Non-Waiver Graduation Rate(https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/2019_Grad_vs_Non-Waiver_Grad_Rates.png)

Indiana State Graduation Rates vs. Non-Waiver Graduation Rates Yearly Average (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/Indiana_State_Graduation_Rates_vs._Non-Waiver_Graduation_Rates_Yearly_Averages.png)

What is the relationship between waiver graduates and school grade?

To begin, let's visualize the school grade data. See the multiline graph below. It showes the number of schools in each letter grade by year. Insights gleened from this visualization of the letter grades is that there may have been a change in grading schools from 2015 to 2016. We speculated that was a result of a new state administration elected to lead the education department. If I had another two weeks, I would look into this further. Another insight is that D and F schools do not add up to many schools.

School Grade Count MultiLine Graph: (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/schoolgradecount.png)

The anova analysis below compares average percent change in graduation rates per school letter grade in 2015. I expected there it be a statistical difference between how high performing schools and lower performing schools use graduation waivers. There was a satistical difference. Also, not all outliers are to be discarted from the data. In the case of schools, the outliers show us problem schools. If I was a state leader in eduation, I would use outliers to pinpoint schools that need help. I would road trip to talk to school administration, teachers, staff, and students in schools that graduating more students who don't meet state requriments for graduation. Was there an natural disaster that year? Did the drug addiction rate skyrocket in these locations? This analysis of the graduation waiver program left us with plenty of question for futher exploration.

anova analysis: (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/schoolgradeanova.png)

Finally, the average percent change from the reported graduation rate to the non-waiver graduation rate were calculated to isolate the waiver graduates for analysis. In bar graphs below, each letter grade's average percent change in grad rate is represented for each year. From 2015 to 2019 the use of graduation waivers went up significantly. That means more students are attending 4 years of high school in Indiana and leaving without meeting the graduation requirments. In a world that requires more and more understanding of S.T.E.M subjects and jobs for unskilled labor are dwindling, this is concerning.I did this analysis on 2015. Out of all of the years obsurved in the data, 2015 data showed the least use of graduation waivers and the least difference between higher performing schools and lower performing schools in that use of waivers. If I did run an anova analysis on the other years we would see even more statistical difference beween the letter grades. For example, the outliers in 2015 showed up to 25% use of graduation waivers. In 2019, the average percent percent change in graudation to non-waiver graduation was over 50%. There is definatly a trend upwards from 2015 tp 2019.

2015 - 2019 Bar Graphs:

(https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/AveragChange15.png) (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/AveragChange16.png) (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/AveragChange17.png) (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/AveragChange18.png) (https://github.com/brittanyschultz114/HS-graduation-rates/blob/main/Output_Data/AveragChange19.png)

What is the relationship between waiver graduatation rates and poverty?

We looked at the relationship between graduation/non-waiver graduation rates and poverty and found some interesting trends. We initially thought there would be a strong correlation between poverty rate and graduation rates, but we found that the correlation was actually moderate to week depending on year and waiver vs. non-waiver. The correlation also weakened over time, which is not an expected result either. Another trend we noticed in the data is that poverty rate decreased across the entire state between 2015 and 2019 while the non-waiver graduation rates also decreased, leading us to believe there are other underlying factors impacting the worsening graduation rates.
