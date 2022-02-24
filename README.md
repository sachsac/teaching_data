# teaching_data
This branch is for my side project(s), which I have conducted using data from my position as a TA at Coding Dojo. No confidential company information was used or disclosed in making said projects.
#### *Updated 2/23/2022*
# Hours Projects
This mini-project involves the TA_Hours_Analysis and TA_Hours_Model. So far, this is a small sample size, which I will continue to grow over time. I will update the notebooks bimonthly in Github, but consistently as I help more students.

I gathered this data independently. I first created a spreadsheet documenting when students were contacting me for assistance. I note the initial contact time (in Eastern/local time), the student's name (although removed from the final product for anonymity), the cohort they are in (using start date for cohort), stack name (what section of the program student was in at time of request), and what day it was (MM/DD/YYYY) that they contacted me. For the time and day, I used Excel formulas to translate time to military time (for easier AI use) and date to day of the week (for analysis purposes). This data reflects helping students outside of live classes.

## Analysis
In this challenge, I analyze which days of the week are most popular and visualize the hours with the highest spikes of students. However, it is skewed, as I have long shifts on certain days, which would result in a higher number of students helped on days I am working more.

During my hours, the highest spikes of activity on Saturdays were shortly after 3 pm, For Wednesdays between 6 pm and 7 pm, Thursdays after 11 pm, of which are my working days.

From my analysis, I visualized the percentage of students approaching me on and off hours, and was astonished to see basically a 50/50 split.

![image](https://user-images.githubusercontent.com/86759538/155433307-edc00e4b-5d3a-4c0c-aa63-fa5638d60eda.png)

A small majority of requests are during off-hours. This suggests there may need to be improvements regarding communicating the TA schedule or via the use of Discord, where a TA is "online" but not available for assisting students.


## Predictive Models

I also experimented with predictive models on the condition I am most concerned with: are students following proper procedure and contacting during my work hours (binary classification)?

Logistic Regression performed the best of the three models I tried: Logistic Regression, KNN, and XGBoost. Logistic regression excels in binary classification models, which is why it performs so well given this data set. With logistic regression model, we have an F1 score (almost like an overall performance metric) of **95%** for the testing set and 100% for the train set. Below is a confusion matrix to show the predictions.

![image](https://user-images.githubusercontent.com/86759538/155434333-fddbb51d-2ef4-4f50-ae28-9ad3da7dcb47.png)

 Again, as mentioned, this will be more reliable as the dataset grows.
