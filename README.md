# Call Center Analysis || Power-BI

### 💠 Project Overview

- The Call Center Analysis project utilizes Power BI to analyze and evaluate key aspects of call center operations, including total calls, resolution rates, abandoned calls, agent performance, and customer 
  satisfaction.
- The analysis highlights patterns in call volume by time and day, identifies top-performing agents, and pinpoints areas needing improvement, such as response times and unresolved issues.
- By providing interactive and visually intuitive dashboards, the project equips stakeholders with actionable insights to optimize resource allocation, improve service quality, and enhance customer satisfaction. - This data-driven approach supports better decision-making to address operational challenges effectively.
- 
### 💠 Problem Statement

-How can we reduce the number of abandoned calls and improve the overall call resolution rates?

- Which agents are performing well, and who requires additional support or training to enhance their efficiency?

- What are the key factors contributing to low customer satisfaction ratings, and how can they be addressed?

- Are there specific days or times when call volumes peak?

- How can we optimize response times and workload distribution among agents to improve service quality?

- What topics or issues generate the highest volume of calls, and how can we proactively address them?

- How can insights from this analysis help in resource planning and enhancing the customer experience?


### 💠 Data Source 
 
 - This dataset is from PwC Switzerland Virtual Internship Program offered by Forage, which containing call records from a customer service center.
 - Each row represents a call with various attributes such as Call Id, Agent, Date, Time, Topic, whether it was Answered (Yes/No), Resolved, Speed of answer in seconds, and Average Talk Duration.

### 💠 Tools Used 
- Microsoft Excel - Data Cleaning
- PowerBI - DAX, Creating Visualizations , Creating Dashboard

### 💠 Data Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting

4. ### 💠 Project dashboard includes:-

➵ Page 1: Calls Analysis

➵ Page 2: Agent Analysis 

## 💠 Insights & Findings

## ✨ Page 1: Calls Analysis

![Screenshot 2024-05-06 150952](https://github.com/purvaphalak/Call_Center_Analysis/assets/148857209/3a60e0f9-95cc-42ea-9d80-986866815490)

### KPI's:

#### ➼ Average Satisfaction Rating:

Rating : 3.40 out of 5, indicating an average level of customer satisfaction.
There is room for improvement in terms of providing a better customer experience.

#### ➼ Total Calls:

5,000 calls were received in total during the selected time frame.

#### ➼ Answered Calls:

4,054 calls (81.08%) were successfully answered.

This indicates a good response rate, but there is a significant number of 946 calls (18.92%) that were abandoned.

#### ➼ Resolved Calls:

Out of the answered calls, 3,646 (72.92%) were resolved successfully.

27.08% of the calls were unresolved, which highlights areas where better resolution processes might be needed.

#### ➼ Average Speed of Answer:

The average time to answer a call was 67.52 seconds, indicating some delays in connecting with customers. Reducing this can improve customer satisfaction.

## ✅ Detailed Visual Analysis:

#### 1] Calls Resolved/Not Resolved by Month:

The breakdown by month shows:
January: Highest number of resolved calls (1,311), but also the most unresolved calls (461).
February and March: Slightly fewer calls than January, but the resolution rates remain consistent.

#### 2] Total Calls by Weekday:

The call volume is highest on Monday (770) and Saturday (768), and slightly lower on weekdays like Tuesday (675).
Insights: Staffing on peak days like Monday and Saturday might need adjustment to handle higher traffic.

#### 3] Total Calls by Hour:

Calls peak between 11 AM to 3 PM, with 12 PM being the busiest hour (590 calls).
The volume drops sharply after 5 PM.
Insights: Agents should be more available during peak hours for better handling of call volumes.

#### 4] Answered and Abandoned Calls by Topic:

Calls related to Streaming and Payment Issues had the highest abandonment rates, despite being common topics.
Technical Support calls were handled relatively well, indicating better resolution processes in that area.

## ✅- Filters and Interactivity:
The dashboard includes several filters for:

Date: Users can adjust the time frame to view specific periods.

Month: Allows analysis of monthly trends.

Agent and Topic: Helps to drill down into individual agent performance or specific call topics.

## ✅ Findings and Recommendations:

#### 1] Call Handling:

- With 946 calls abandoned, improving the availability of agents during peak hours can enhance response rates.

#### 2] Customer Satisfaction:

- An average rating of 3.40 indicates the need for better training, faster resolutions, and improved processes to enhance customer experience.

#### 3] Resolution Rates:

- While 72.92% resolution is good, focusing on unresolved calls can further improve customer trust and retention.

#### 4] Peak Hours and Days:

- Reinforce staffing during peak times (11 AM - 3 PM) and busier days (Monday and Saturday) to handle higher call volumes efficiently.

#### 5] Topic-Specific Insights:

- Focus on Streaming and Payment-related issues as these areas see high abandonment rates, which can negatively impact customer perception.

## ✨ Page 2: Agent Analysis

![Screenshot 2024-05-06 151010](https://github.com/purvaphalak/Call_Center_Analysis/assets/148857209/25dd8e7e-e99f-4c3f-bd9e-e439af11c18d)

#### ➼ Total Agents:
 
 The dashboard analyzes the performance of 8 agents.
 
####  ➼ Total Calls:

5,000 calls were received, with 4,054 calls (81.08%) answered.

#### ➼ Most Issue Resolved:

Jim resolved the highest number of calls (485 calls) among all agents, showcasing exceptional problem-solving efficiency.

#### ➼ Most Calls Missed:

Diane missed the most calls (132 calls) during this period, indicating areas for improvement in her availability or call-handling capacity.

#### ➼ Highest Customer Satisfaction Rating:

Martha achieved the highest satisfaction rating of 3.47 out of 5, showing her ability to handle calls with high-quality service.

#### ➼ Quickest to Answer:

Diane had the fastest average speed of answer at 66.2 seconds, highlighting her responsiveness.

## ✅ Detailed Visual Analysis:

#### 1] Answered Calls by Agents:

- The highest number of calls answered was by Jim (536 calls), followed by Martha (514 calls).
  
- Stewart answered the least number of calls (477 calls), indicating either fewer assigned calls or potential inefficiency.

#### 2] Resolved Calls by Agents:

- Jim leads in resolved calls (485 resolved out of 536 answered), reflecting his efficiency.
  
- Joe has the lowest number of resolved calls (436 resolved out of 484 answered), which might indicate challenges in resolving customer issues.

#### 3] Total Calls by Agent:

- Jim handled the most total calls (638 calls), while Stewart handled the least (582 calls).
  
- The relatively balanced distribution suggests a fair allocation of calls among agents.

#### 4] Average Speed of Answer by Agent:

- Diane is the quickest to respond (66.2 seconds), while Joe is the slowest (71.5 seconds).
  
- Faster response times generally contribute to better customer satisfaction.

#### 5] Satisfaction Rating by Agent:

- Martha has the highest rating (3.47), followed by Dan (3.45).
  
- Joe has the lowest rating (3.33), signaling areas for improvement in his service quality.
- 
#### 6] Agent Statistics Table:

Provides a clear overview of each agent's performance in terms of:
- Answered Calls
- Abandoned Calls
- Resolved Calls
- Average Satisfaction
- Average Speed of Answer
For instance, Martha has a low abandonment rate (124 calls) and high customer satisfaction, making her one of the top-performing agents.

## ✅ Findings and Recommendations:

#### 1] Top Performers:

Jim is the top performer in terms of volume, resolving the highest number of calls.
Martha excels in customer satisfaction, reflecting a customer-focused approach.

#### 2] Improvement Areas:

Diane needs to address her high missed-call rate (132 missed calls), despite her quick response times.
Joe should focus on improving resolution rates and customer satisfaction.

#### 3] Balanced Workload:

Call volumes are fairly distributed among agents, but there is scope to adjust workloads for agents with higher abandonment rates to improve efficiency.

#### 4] Response Times:

- Improving the overall average speed of answer (67.52 seconds) could enhance customer satisfaction and reduce abandoned calls.
  
- This dashboard provides actionable insights for managers to recognize high-performing agents, address challenges in low-performing areas, and optimize the call center's overall efficiency.

### ✅ Overall Insights:

#### ➼ Call Metrics:
Out of 5,000 total calls, 81% (4,054 calls) were answered, while 946 calls (19%) were abandoned.
72.92% of answered calls were resolved, indicating room for improvement in issue resolution efficiency.

#### ➼ Call Volume Trends:
Monday and Saturday had the highest call volumes, while weekdays like Tuesday had comparatively lower volumes.
Peak call hours were observed between 10 AM and 2 PM, with a notable drop after 5 PM.

#### ➼ Agent Performance:
Jim resolved the highest number of issues (485) and handled the most calls, while Diane had the most missed calls.
Martha had the highest average satisfaction rating (3.47), while Joe had the lowest (3.33).
Becky had the fastest average speed of answer (65.3 seconds), while Joe had the slowest (71.5 seconds).

#### ➼ Customer Satisfaction:
The average satisfaction rating across the call center was 3.4 out of 5, indicating a need to address service quality and efficiency.

## 💠 Summary :

➤ The Call Center Analysis project evaluates call handling efficiency, agent performance, and customer satisfaction from January to March 2021. 

➤ While most calls (81%) were answered, 19% were abandoned, and only 72.92% of answered calls were resolved. 

➤ The analysis highlights peak call times, uneven workload distribution, and gaps in customer satisfaction. 

➤ Agent performance varies significantly, with some agents excelling in issue resolution and response times, while others need support to meet expectations.

## 💠Conclusion :-

➤ The analysis underscores the need to improve call resolution rates, reduce abandoned calls, and address variations in agent performance to enhance overall efficiency.
  
➤ Focusing on customer satisfaction and addressing high call volumes during peak hours can lead to a better customer experience.
  
➤ By implementing targeted training, improving resource allocation, and leveraging insights from this analysis, the call center can optimize operations and improve service quality effectively.








