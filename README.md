## Active_Users_and_Activity

#### Technology Stack:
Google Sheets(formulas, functions, forecasting, charts, transformation, pivot tables)

#### Project Description:
In this project, I utilized Google Sheets to analyze user data and activity. The primary objectives and tasks accomplished include:

1. Active Users Sheet:
Calculated various user age statistics such as Average Age, Standard Deviation, Interquartile Range, Median, 10th, and 90th Percentiles of Age.

2. Activity Sheet:
Added the "week_start_date" column, using formulas to derive the week start date for each entry in the "activity_date" column.

3. DAU (Daily Active Users) Sheet:
Created a new sheet, "DAU," with a column for "activity_date," containing unique activity dates from the "activity" sheet.
Calculated and displayed the unique number of users active on each corresponding date.
Calculated the "week_start_date" column's values.

4. WAU (Weekly Active Users) Sheet:
Created the "WAU" sheet with a "week_start_date" column, containing unique week start dates from the DAU sheet.
Displayed the unique number of users active in each corresponding week.
Calculated the Average DAU (Average Daily Active Users) for each week.
Calculated the DAU/WAU (Daily Active Users to Weekly Active Users) ratio for each week.
Added 20 new lines to project future weeks and forecasted WAU and DAU values for those weeks.

5. Charts:
Built four charts:
Bar chart on the "Active Users" page displaying the number of users for each language.
Pie chart on the "Active Users" page showing the breakdown of users by having an older device model.
Data chart on the "WAU" page, with weeks on the horizontal axis and two vertical axes: WAU and DAU/WAU.
Data chart on the "WAU" page, with weeks on the horizontal axis and WAU values on the vertical axis, including a polynomial trend line.

6. Data Transformation:
Split the "game_activity_name" column in the "activity" sheet into two parts: game name and activity name.
Consolidated eight activity names into five activity types and displayed them in a separate column in the "activity" sheet.
Created a column for user language and populated it using data from the "Active Users" sheet.
Derived three columns from the "activity_date" column: Activity Month, First Activity Month, and Activity Month Number.

7. Cohort Analysis:
Created a new "Cohort Analysis" sheet with a pivot table using data from the "activity" sheet.
Displayed the Activity Month Number in rows and the number of unique users as values in the pivot table.
Visualized the number of users in each month of activity using a line chart.

8. Cohort Analysis 2:
Created a separate "Cohort Analysis 2" sheet with a pivot table using data from the "activity" sheet.
Displayed First Activity Month in rows, Activity Month Number in columns, and the number of unique users as values.
Created a table below the pivot table displaying retention rates instead of user counts.
Implemented conditional formatting for both tables to highlight significant values.
Added three slices: game name, activity type, and user language for enhanced analysis.

#### Link:
https://docs.google.com/spreadsheets/d/1uieUg2xaLr3mB10U2lgoPqabnYIBWW7wqOp-cSh1LhM/edit?usp=sharing

#### Skills:
Google Sheets, Cohort Analysis
