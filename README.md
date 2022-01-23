# teaching_data
This branch is for my side project(s), which I have conducted using data from my position as a TA at Coding Dojo. No confidential company information was used or disclosed in making said projects.

# Hours Projects
This mini-project involves the TA_Hours_Analysis and TA_Hours_Model. So far, this is a small sample size, which I will continue to grow over time. I will update the notebooks bimonthly in Github, but consistently as I help more students.

I gathered this data independently. I first created a spreadsheet documenting when students were contacting me for assistance. I note the initial contact time (in Eastern/local time), the student's name (although removed from the final product for anonymity),  the cohort they are in (using instructor's name), and what day it was (MM/DD/YYYY) that they contacted me. For the time and day, I used Excel formulas to translate time to military time (for easier AI use) and date to day of the week (for analysis purposes). This data reflects helping students outside of live classes.

## Analysis
In this challenge, I analyze which days of the week are most popular and visualize the hours with the highest spikes of students. However, it is skewed, as I have long shifts on certain days, which would result in a higher number of students helped on days I am working more.

During my hours, the highest spikes of activity on Saturdays were shortly after 3 pm, For Wednesdays between 6 pm and 7 pm, Thursdays after 11 pm, of which are my working days.

From my analysis, I visualized the percentage of students approaching me on and off hours, and was astonished to see basically a 60/40 split.

![image](https://user-images.githubusercontent.com/86759538/150689462-f2978087-5146-4eb0-b96e-0d232b82c90a.png)

This suggests there may need to be improvements regarding communicating the TA schedule or via the use of Discord, where a TA is "online" but not available for assisting students.


## Predictive Models

For fun, I also experimented with predictive models on the condition I am most concerned with: are students following proper procedure and contacting during my work hours (binary classification)?

XGBoost performed the best of the three models I tried: Logistic Regression, KNN, and XGBoost. The model struggled slightly with the smaller class, the contact that *was* outside of hours; even so with an overall 85% accuracy.

![image](https://user-images.githubusercontent.com/86759538/150689616-3fc55e8a-2d0c-4a23-9abe-c1f23f57a0a6.png)

 Again, as mentioned, this will be more reliable as the dataset grows.
