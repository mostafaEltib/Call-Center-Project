

https://github.com/mostafaEltib/Call-Center-Project/assets/108897691/24cc04bb-1fa7-43fb-9bf8-092142f95eb1


# Call-Center-Project
## Implementation a Call center Data Analysis Project On Customer Service Career using Power_BI .


After I read multiple articles about it , I want to Illustrate what is Call Center ,
In today's fast-paced business environment, call centers play a crucial role in delivering exceptional customer service. To optimize operations and ensure seamless customer interactions,
The call center job involves addressing customer inquiries and providing support through phone interactions. Agents aim to answer calls promptly, resolve issues effectively, and ensure customer satisfaction.
<br />
<br />

### Based on MetaData I asked effective questions to enhance Company performance(asked questions) .


(KPIs)<br />
What is  total number of Calls?<br />
What is Count of agents and agent performance?<br />
What is  total number of  Answered Calls And missed calls ?<br />
What is  percentage of resolved Calls and not resolved Calls ?<br />
What is the distribution of topics for the calls(Technical support,streaming,…)?<br />
What is the distribution of clients Rating?<br />
Who is from the agents  is most (calls answer,calls resolver)?<br />
What is total calls  by hours?<br />
What is sum of duration of calls by  each agent?<br />
What is performance of Topic and are it affect on clients rating?<br />
<br />

### (Data processing)

Load Dataset to Power query editor and transform Data<br />
<br />
 ◦ Chang Data type for columns<br />
 ◦ Removed unwanted columns<br /> 
 ◦ Handling null values in columns<br /> 
 ◦ From (AvgTalkDuration) column I added tow column seconds and minutes<br /> 
 ◦ Merge columns (minute,second) to get duration of calls in another format<br />
 ◦ Simplify other columns<br />
 ◦ Add tow table using groupby to illustrate agents performance and topic performance(I used tow table to create tow custom tootips)<br />

### Load and apply Transformation Data
Created tow calculated column for answer and missed calls<br /> 
Created tow calculated column for solved and not solved calls<br />
Created DAX Measures table that contains all measures<br />
 <br />
### Designed a Dashboard to Answer questions and Monitor the the company performance<br /> 
<br />
After understanding business need and finishing data analysis,
and answering  the questions<br /> 
This is some recommendation <br />
<br />
1.total un answered calls 18.92 % of total calls,the manager should increase the agents <br />
2.percentage of calls not resolved 27.08% of total calls ,should optimise agent training to handle topics problem  especially streaming and technical support issues <br />
3.encourage Jim and Dan for their achievements <br />

### project lifecycle 
1-Understanding metadata and business needs <br />
2-Data transformation <br />
3-Visual representation <br />
4-Dashboard design
