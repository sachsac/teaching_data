# teaching_data
This branch is for my side project(s), which I have conducted using data from my position as a TA at Coding Dojo. No confidential company information was used or disclosed in making said projects.
#### *Last update to README 4/30/2022*
# Hours Projects
This mini-project involves the TA_Hours_Analysis and TA_Hours_Model. So far, this is a small sample size, which I will continue to grow over time. I will update the notebooks bimonthly in Github but consistently as I help more students. 

I gathered this data independently. I first created a spreadsheet documenting when students were contacting me for assistance. The information in the spreadsheet are: the initial contact time (in Eastern/local time); the student's name (although removed from the final product for anonymity); the Cohort they are in (using start date for Cohort); stack name (what section of the program student was in at the time of request); and what day it was (MM/DD/YYYY) that they contacted me. For the time and day, I used Excel formulas to translate time to military time (for easier AI use) and date to day of the week (for analysis purposes). 

Later, additional information was collected: the end time for the assistance (when the student's issue is solved) and creating a calculation of total time assisted by subtracting end-time by start time. 

This data reflects helping students outside of live lectures. 

I will not be able to post my dataset itself, as it is non anonymized. The data used in notebooks, however, do not display Student names.

# Analysis
## Description
In this challenge, I analyze which days of the week are most popular and visualize the hours with the highest spikes of students. However, it is skewed, as I have long shifts on certain days, no shift at all on some, and shorter shifts. The variety of hours worked results in a higher number of students helped when I am working for more hours.

Communication between students and instructing staff occurs on the app Discord. Initially, I utilized a one Discord account for personal and TA reasons. Despite a public TA schedule, students contacted a TA that may show as "online" but were not available to assist students. The team sensed this might be why I, in particular, had more off-hour contact than other TAs. Because of this, I had two iterations of my data, before separate Discord accounts and after (3/1/2022 and onwards). 

## Off-Hours Contact
From my analysis, I visualized the percentage of students approaching me on and off-hours, 

### First Analysis
Before the separation of accounts, there was a noticeable amount of off-hours contact. With this in mind, I was still astonished to see a 50/50 split.

![image](https://user-images.githubusercontent.com/86759538/166121293-abaa41cf-a3df-49de-a51e-609e8f767179.png)

There was even a slight majority of the contact occurring off hours.

### Second Analysis
After the split of the accounts, there was a drastic improvement. The off-hours contact dropped from > 50% to < 25%. 

![image](https://user-images.githubusercontent.com/86759538/166123952-b1492bc3-76bd-4730-8b43-77283de7ddff.png)

## Days of the Week
### First Analysis
The days I worked in this iteration were Tuesdays (effective January 11th, 2022), Wednesdays, Thursdays (decreased hours starting January 20th, 2022), and Saturdays.

In this iteration, Saturdays and Wednesdays were the busiest shifts. Saturdays were busiest towards the middle of the shift, and Wednesday got more active towards the end (after the lecture).

![image](https://user-images.githubusercontent.com/86759538/166121893-5844edb8-94cd-4a73-9ca1-1ec915b8c249.png)

### Second Analysis
Schedule changes after or during the second analysis include: ceased Tuesday and Thursday hours after March 24th, 2022.

In this second iteration, Saturdays' popularity dwindled. Tuesdays after around lecture time and Wednesdays before lecture spiked in popularity. 

Tuesday night was just as popular as a weekend date (Saturday), though, keep in mind that I worked more Saturdays than Tuesdays, meaning it took more weeks to go by for Saturday to accrue enough days that Tuesday nights had in just three weeks’ time. 

![image](https://user-images.githubusercontent.com/86759538/166123930-0063501d-87c9-4403-a45a-e9a3104c78a0.png)


## Cohort

### First Analysis
I started working on November 8th, 2022, so all data is between then and February 28th, 2022. The cohorts which required the most assistance during this timeframe were the 11/29 and 1/24 cohorts.

![image](https://user-images.githubusercontent.com/86759538/166122466-91756d76-2795-4e03-93ca-e6cea4965d6c.png)


All of the cohorts in this period were not enrolled during the timespan of this data collection. However, even with this in mind ** the 1/24 Cohort still had the highest numbers for assistance.** The 11/29 cohort was in the program the most out of the cohorts in the data set; In that timeframe, 1/24 had more needs in 36 days than 11/29 did in 92 days.

### Second Analysis
I have worked with the 1/24 cohort the most from the beginning of March and onwards. 
![image](https://user-images.githubusercontent.com/86759538/166123919-02763d32-df05-431e-afdd-deb560864865.png)

The cohorts that had little time (or none) in the program were the 11/29 and 10/11 cohorts, so this makes sense; they would have fewer numbers. The 3/21 and 4/18 cohorts had not yet started, so they also have fewer numbers given less time in the program. 

It is worth noting that 1/24 and 2/21 cohorts were in the program the entirety from 3/1/2022 (the beginning of the second analysis) to today (4/30); in that timeframe, 1/24 has had more needs than 2/21. 


## Stack

### First Analysis
![image](https://user-images.githubusercontent.com/86759538/166122806-bd6610d2-fd37-44b0-893f-64a0b16f6e54.png)

The order of the stacks is: Data Fundamentals, Machine Learning, and then Advanced Machine Learnings. Interestingly, the number of requests decreased as each stack continued. So the last stack of the course had the least amount of requests, and the first stack of the program had the most. 

I felt this demonstrated the students becoming more familiar with basic concepts and learning independent troubleshooting the further into the program they went.

### Second Analysis
![image](https://user-images.githubusercontent.com/86759538/166123891-f6a9e229-575f-4e00-ac96-f137e4c3a93d.png)

Similar to the first analysis, Data Fundamentals remains in the stack with the most requests for assistance. However, Advanced Machine Learning had more requests than Machine Learning, which is different from the first.

This conflicts with my previous hypothesis. The difference potentially is that students have to finish their second project presentations during the Advanced Machine Learning stack. I believe that during this time frame, more students happened to need help with their projects.

## Time of Assistance Analysis
Documenting the end time of students' assistance meant I could then analyze time spent with students. The total time spent on an issue also allows us further insight into the previous sections, Stacks and Cohorts, to see the number of interactions and how much time was spent with these students. This data can be compared to the second analysis from above. I started tracking times during that (though the above five days' worth of data regarding time spent together was not recorded; therefore, those entries (rows) were removed from the analysis below).

### Cohort Time


![image](https://user-images.githubusercontent.com/86759538/166123960-4679568c-4b01-4d68-adf1-ad60f12a601b.png)

![image](https://user-images.githubusercontent.com/86759538/166123971-d0572102-e4df-4524-9865-890985f1799f.png)

In the Cohort section above, we learned that the 1/24 cohort had the most interaction, and it also correlated with the most time spent, and 2/21 had the second most time spent together. Besides those two, though, the 3/21 cohort, despite having more interactions, has less time than 4/18; the 4/18 stack thus far has required longer sessions per meet than 3/21.

The information for the 10/11 cohort is skewed, as there was only one interaction with this student while they were alumni. So the average for that CohortCohort represents only one interaction.

3/21 CohortCohort has, on average, had the shortest sessions, with 1/24 requiring the most time per session.

### Stack Time

![image](https://user-images.githubusercontent.com/86759538/166123978-8dff67c7-28fa-4a41-b49e-fffbb8f87f35.png)

![image](https://user-images.githubusercontent.com/86759538/166123979-c0fd9bed-362b-4ad1-a8f8-f0d630dbf456.png)


If we remember, Data Fundamentals drastically had more requests for help from TAs than the other options. However, as we can see, the requirements for these sessions (average) are much lower than the other stacks. 

The stack requiring the most time for issues is the Advanced Machine Learning stack. This stack includes more complex data models and the final individual project, which makes sense for why these sessions may be lengthy and time-consuming. 

The data fundamentals stack represents more straightforward problems, which do not require as much time to solve with a student.

In conclusion, quality is not the same as quantity! 

Again, please note the alumni data, which is representative of one interaction. 

## Student Counts
My final analysis using this data involved counting the number of times each student contacted me. This section combines our data from both before and after account separation. 

![image](https://user-images.githubusercontent.com/86759538/166124001-e16e47b5-b9c4-49b7-a076-6e7b745d8cec.png)

It is difficult to explain in a graph. The above bar chart shows that 26 students contacted me only once throughout my data. The most contacts an individual and I had were 12 times, and the median amount of interactions was two. The 8 and 12 interaction students were considered outliers.

![image](https://user-images.githubusercontent.com/86759538/166123996-f4d661f5-a64e-4342-a1d9-c06ea4268c64.png)

# Predictive Models

I also experimented with predictive models on two topics: are students following proper procedure and contact during my work hours (binary classification), and can we predict the amount of time (in minutes) a student will need assistance per session (regression).

Multiple models were used to make machine learning work for these two questions. There are not enough features in the dataset to create a reliable model at this current state. Noth the classification and regression problems were inefficient for machine learning models.


