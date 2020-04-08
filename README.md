# Women-in-the-loop

![](Hackathon_Banner_Final.jpeg)

LearnX Sales Forecasting

# Problem statement

LearnX is an online learning platform aimed at professionals and students. LearnX serves as a market place that allows instructors to build online courses on topics of their expertise which is later published after due diligence by the LearnX team. The platform covers a wide variety of topics including Development, Business, Finance & Accounting & Software Marketing and so on.

Effective forecasting for course sales gives essential insight into upcoming cash flow meaning business can more accurately plan the budget to pay instructors and other operational costs and invest in the expansion of the business.

Sales data for more than 2 years from 600 courses of LearnX's top domains is available along with information on:-

•	Competition in the market for each course

•	Course Type (Course/Program/Degree)

•	Holiday Information for each day

•	User Traffic on Course Page for each day

Your task is to predict the course sales for each course in the test set for the next 60 days.

# Data Dictionary

The *Train data* (Historical Sales Data) has following attributes:-

|Variable	|Definition|
|---------|----------|
|ID|	Unique Identifier for a row|
|Day_No|	Day Number|
|Course_ID|	Unique ID for a course|
|Course_Domain|	Course Domain (Development, Finance etc.)|
|Course_Type	|Course/Program/Degree|
|Short_Promotio|	Whether Short Term Promotion is Live|
|Public_Holiday	|Regional/Public Holiday|
|Long_Promotion	|Whether Long Term Promotion is Live for the course|
|User_Traffic	|Number of customers landing on the course page|
|Competition_Metric	|A metric defining the strength of competition |
|Sales	(Target)| Total Course Sales|


The *Test data* (Next 60 Days)

This file contains the store and day number for which the participant needs to submit predictions/forecasts

|Variable|	Definition|
|--------|------------|
|ID	|Unique Identifier for a row|
|Day_No	|Day Number|
|Course_ID	|Unique ID for a course|
|Course_Domain|	Course Domain (Development, Finance etc.)|
|Course_Type	|Course/Program/Degree|
|Short_Promotion|	Whether Short Term Promotion is Live|
|Public_Holiday	|Regional/Public Holiday|
|Long_Promotion|	Whether Long Term Promotion is Live for the course|
|Competition_Metric|	A metric defining the strength of competition|

*Sample Submission*

This file contains the exact submission format for the forecasts. Please submit csv file only.

|Variable	|Definition|
|---------|----------|
|ID	|Unique Identifier for a row|
|Sales	(Target) |Total Course Sales predicted from the test set|

# Evaluation Metric

The evaluation metric for this competition is 1000*RMSLE where RMSLE is Root of Mean Squared Logarithmic Error across all entries in the test set.

### Private Score  - 225.769782233722      Rank - 237

### Public Score  - 223.401724130756      Rank - 254
