---
title: SDE I Internship @ Amazon Connections Scheduling Service Team
---
In May of 2021, I joined the Amazon Connections Scheduling Service Team. As a team under the HR organization, the Connections team is consisted out of hundreds of engineers, product managers and data sciensts, and its main responsbility to generate daily survey questions to all Amazon employees based on their levels, positions and other characteristics. 

The Connections Scheduling Service Team is mainly responsible for schduling the survey questionnaires to employees at suitable time frames. Currently, the team uses a greedy algorithm for generating the schedules for the questions, and is planning to use an external optimization tool, Xpress, to achieve in the future. 

Xpress is a linear programming tool that is primiarly used for problems related to optimization. (I personally view Xpress as a giant linear algebra solver). 

My main responsbility for this internship is to create a new version of our team's current algorithm that utilizes Xpress and deploy such algorithm through AWS Lambda. I also worked with several othe AWS technologies, notably AWS S3 (retrieve exisitng data from previous surveys), AWS Step Functions (chaining a series of AWS Lambda functions) and AWS Simple Notification Services (for notifying the users).