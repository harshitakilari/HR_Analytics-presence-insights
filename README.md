# HR_Analytics-presence-insights

This is a project series from the youtube channel code basics where real data from AtliQ company is taken. Data Cleaning and Transformation are done Dynamically, learned to use Power BI and Matrics, and created a report to create insights for HR managers or Stakeholders.

**Dataset**
[Attendance Sheet 2022-2023_Masked.xlsx](https://github.com/harshitakilari/HR_Analytics-presence-insights/files/12207317/Attendance.Sheet.2022-2023_Masked.xlsx)

* Dataset contains the data about the day-offs(sick leave, paid leave, menstrual leave ) and also included the type of work ( work from home, half work from home) and was described as
  
![Attendence_Key](https://github.com/harshitakilari/HR_Analytics-presence-insights/assets/108713558/ae7bbeed-4b73-4080-962a-48976e2c3191)

**Objective**

The objective of the company is to understand the working preference of people in the company as the company is in a hybrid mode and the reason behind the leaves as that can help the company to understand the situation so that they can take some precautionary measures if its a sick leave or can schedule a meeting on a day when majority members are present.
* Requirements
  1. The percentage of people present in a day/week/month?
  2. How many employees are taking sick leave?
  3. How many are working from home?
     
**MyWork**

* Difficulty loading the Excel workbook into Power BI the dataset was raised as there were multiple sheets. **Reference_used**: https://blog.crossjoin.co.uk/2018/07/09/power-bi-combine-multiple-excel-worksheets/
  
* Measures used:
  
   ![Measure_table](https://github.com/harshitakilari/HR_Analytics-presence-insights/assets/108713558/ccf29b4a-0611-4007-bbd9-5080452860f8)
  
* Final Data :
  
   ![Final_data_table](https://github.com/harshitakilari/HR_Analytics-presence-insights/assets/108713558/3d5ab074-6863-4bd5-984b-7dcc3c969d09)

**Final_Report**

![Presence_Dashboard](https://github.com/harshitakilari/HR_Analytics-presence-insights/assets/108713558/4e5bd48a-e3d2-4a50-93c5-e600498a745b)

**Insights_drawn**

* In June the Percentage of People working from home is higher compared to April
* On Tuesdays the presence percentage is maximum.
*  As June is approaching the Presence percentage is declining as the trend in sick leaves percentage is increased.

**What** **I** **Learned**

* Basics of Power BI and its metrics.
* Calculating functions in DAX.
* Dashboarding Techniques
* How to provide real insights for the clients/Stakeholders.
* How to set up some functions for real-time Business needs like Sending Alerts( Triggers), Automate Data Gathering( as data is updated), and Access Privileges for employees.



