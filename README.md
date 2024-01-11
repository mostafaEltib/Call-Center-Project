# Call-Center-Project
Implementation a Call center Data Analysis Project On Customer Service Career using #Power_BI .


After I read multiple articles about it , I want to Illustrate what is Call Center ,
In today's fast-paced business environment, call centers play a crucial role in delivering exceptional customer service. To optimize operations and ensure seamless customer interactions,
The call center job involves addressing customer inquiries and providing support through phone interactions. Agents aim to answer calls promptly, resolve issues effectively, and ensure customer satisfaction.

Based on Data I asked effective questions to enhance Company performance.


(KPIs)
What is  total number of Calls?
What is Count of agents and agent performance?
What is  total number of  Answered Calls And missed calls ?
What is  percentage of resolved Calls and not resolved Calls ?
What is the distribution of topics for the calls(Technical support,streaming,…)?
What is the distribution of clients Rating?
Who is from the agents  is most (calls answer,calls resolver)?
What is total calls  by hours?
What is sum of duration of calls by  each agent?
What is performance of Topic and are it affect on clients rating?

Then(Data processing)

Load Dataset to Power query editor and transform Data

 ◦ Chang Data type for columns
 ◦ Removed unwanted columns 
 ◦ Handling null values in columns 
 ◦ From (AvgTalkDuration) column I added tow column seconds and minutes 
 ◦ Merge columns (minute,second) to get duration of calls in another format
 ◦ Simplify other columns
 ◦ Add tow table using groupby to illustrate agents performance and topic performance(I used tow table to create tow custom tootips)

Load Data
Created tow calculated column for answer and missed calls 
Created tow calculated column for solved and not solved calls
Created DAX Measures table that contains all measures
 
Designed a Dashboard to Answer questions and Monitor the the company performance 

After understanding business need and finishing data analysis 
And answering  the questions 
This is some recommendation 

1.total answered calls 18.92 % of total calls,the manager should increase the agents 
2.percentage of calls not resolved 27.08% of total calls ,should optimise agent training to handle topics problem  especially streaming and technical support issues 
3.encourage Jim and Dan for their achievements 

 project lifecycle 
1-Understanding metadata and business needs 
2-Data transformation 
3-Visual representation 
4-Dashboard design
