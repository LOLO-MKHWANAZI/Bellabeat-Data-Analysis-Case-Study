# Bellabeat-Data-Analysis-Case-Study!



![Run-for-Fitness-SheThePeople1](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/0c79d73d-e0b5-4439-b7d7-a956fd3104c4)


## Introduction
Welcome to the Bellabeat Data Analysis Case Study! In this project, I step into the role of a junior data analyst on the marketing analytics team at Bellabeat, a pioneering company in the realm of health-focused smart devices for women. This journey involves engaging in real-world tasks, interacting with various team members, and ultimately developing a portfolio-ready case study showcasing my skills and insights.

## Scenario
Bellabeat, founded by Urška Sršen and Sando Mur, is a technology-driven company dedicated to manufacturing smart wellness products tailored specifically for women. Since its inception, Bellabeat has rapidly grown, positioning itself as a leader in the wellness tech market.

### Objective
As a junior data analyst, my task is to delve into smart device usage data to uncover insights that could propel Bellabeat's marketing strategy forward. Urška Sršen, the co-founder and Chief Creative Officer, believes that analyzing this data holds the key to unlocking new growth opportunities for the company.

### Characters and Products
#### Characters
- **Urška Sršen**: Co-founder and Chief Creative Officer of Bellabeat.
- **Sando Mur**: Mathematician and Bellabeat's co-founder, a key member of the executive team.
- **Bellabeat Marketing Analytics Team**: A team of data analysts responsible for guiding Bellabeat's marketing strategy.

#### Products
- **Bellabeat App**
- **Leaf**: Classic wellness tracker
- **Time**: Wellness watch
- **Spring**: Smart water bottle
- **Bellabeat Membership**

### About the Company
Bellabeat's journey began in 2013 when Urška Sršen utilized her artistic background to develop beautifully designed technology aimed at empowering women worldwide. By collecting data on activity, sleep, stress, and reproductive health, Bellabeat has provided women with invaluable insights into their health and habits.

## Ask
### Business Task
To analyze smart device usage data and gain insights into how consumers use non-Bellabeat smart devices. Then, select one Bellabeat product to apply these insights to in the marketing strategy presentation.

### Guiding Questions
- What are some trends in smart device usage?
- How could these trends apply to Bellabeat customers?
- How could these trends influence Bellabeat's marketing strategy?

### Key Tasks
- Identify the business task.
- Consider key stakeholders.

### Deliverable
A clear statement of the business task.

### Next Steps
- Define the specific objectives and metrics for analysis.
- Identify key stakeholders who will be involved in the analysis and decision-making process.

## Prepare
### Data Sources
For this project, I will use the following dataset:
- **FitBit Fitness Tracker Data** (CC0: Public Domain, dataset made available through Mobius): This Kaggle dataset contains fitness tracker data from thirty Fitbit users, including minute-level output for physical activity, heart rate, and sleep monitoring. The dataset includes information about daily activity, steps, and heart rate, providing valuable insights into users' habits.

### Data Cleaning and Organization
Before diving into the analysis, I will ensure that the data is cleaned and organized appropriately:
1. **Download Data**: I'll download the FitBit Fitness Tracker Data from the provided source.
2. **Storage**: I'll create a folder on my desktop or Drive to house the files, using appropriate file-naming conventions.
3. **File Organization**: I'll unzip the files and organize them within the designated folder.
4. **Data Verification**: I'll verify the integrity of the data to ensure it is reliable for analysis.
5. **Data Import**: I'll import the dataset into R for further analysis.

### Key Tasks
- Download data and store it appropriately.
- Identify how it's organized.
- Sort and filter the data.
- Determine the credibility of the data.

### Deliverable
A description of all data sources used.

### Next Steps
Once the data is cleaned and organized, I'll proceed to the processing phase to prepare it for analysis.

## Process
### Data Processing
In this phase, I'll process the data to prepare it for analysis. This involves tasks such as checking for errors, choosing appropriate tools, transforming the data, and documenting the cleaning process.

### Key Tasks
- **Check for Errors**: I'll carefully examine the data for any errors or inconsistencies that may affect the analysis.
- **Choose Tools**: I've selected R and RStudio as the tools for data analysis. R provides powerful tools for statistical analysis and data visualization, while RStudio offers an integrated development environment (IDE) for data science projects.
- **Data Transformation**: I'll transform the data into a format that is suitable for analysis. This may involve aggregating data, creating new features, or handling missing values.
- **Documentation**: I'll document the cleaning and manipulation of the data to ensure transparency and reproducibility of the analysis.

### Deliverable
Documentation of any cleaning or manipulation of data.

### Next Steps
Once the data is processed, I'll move on to the analysis phase to uncover insights and trends.

## Analyze
### Data Analysis
In this phase, I'll analyze the processed data to uncover insights, trends, and relationships. This involves tasks such as organizing the data for analysis, performing calculations, identifying patterns, and drawing conclusions.

### Key Tasks
- **Aggregate Data**: I'll organize the data in a way that is useful and accessible for analysis. This may involve grouping data by relevant variables or time periods.
- **Organize and Format Data**: I'll ensure that the data is properly formatted and structured for analysis.
- **Perform Calculations**: I'll calculate relevant metrics, such as averages, totals, or percentages, to gain deeper insights into the data.
- **Identify Trends and Relationships**: I'll examine the data to identify trends, patterns, and relationships that may be relevant to the business questions.

### Deliverable
A summary of the analysis, including key findings and insights.

### Next Steps
Once the analysis is complete, I'll proceed to the sharing phase to present the findings and insights to stakeholders.

## Share
### Data Visualization and Presentation
In this phase, I'll create data visualizations and prepare to share my findings with stakeholders. Effective data visualizations can help communicate insights and recommendations clearly and persuasively.

### Key Tasks
- **Determine the Best Way to Share Findings**: I'll consider the audience and the most effective way to communicate the key findings and insights. This may include creating presentations, reports, or dashboards.
- **Create Effective Data Visualizations**: I'll use data visualization tools and techniques to create visuals that highlight the most important insights from the analysis. This may include charts, graphs, or interactive visualizations.
- **Present Findings**: I'll prepare to present the findings and insights to stakeholders in a clear and engaging manner. This may involve preparing a formal presentation or leading a discussion.
- **Ensure Accessibility**: I'll ensure that the presentation is accessible to the audience, taking into account factors such as language, visual impairment, and technical expertise.

### Deliverable
Supporting visualizations and key findings presented in a format suitable for the audience.

### Next Steps
Once the findings are shared with stakeholders, I'll move on to the final phase of the project: acting on the insights to drive business decisions.

## Data Analysis and Visualization
### Combine the Data
Ensure the data from the two CSV files is combined into a single dataframe.

### Visualize the Data
Create various plots to understand the activity trends, relationships, and distributions.

### Save the Results
Save the cleaned data and summary statistics to CSV files.

Here is a detailed plan:




Rows: 457 Columns: 15                                                                   
── Column specification ────────────────────────────────────────────────────────────────
Delimiter: ","
chr  (1): ActivityDate
dbl (14): Id, TotalSteps, TotalDistance, TrackerDistance, LoggedActivitiesDistance, ...

ℹ Use `spec()` to retrieve the full column specification for this data.
ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
Rows: 940 Columns: 15                                                                   
── Column specification ────────────────────────────────────────────────────────────────
Delimiter: ","
chr  (1): ActivityDate
dbl (14): Id, TotalSteps, TotalDistance, TrackerDistance, LoggedActivitiesDistance, ...

ℹ Use `spec()` to retrieve the full column specification for this data.
ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
spc_tbl_ [1,397 × 15] (S3: spec_tbl_df/tbl_df/tbl/data.frame)
 $ Id                      : num [1:1397] 1.5e+09 1.5e+09 1.5e+09 1.5e+09 1.5e+09 ...
 $ ActivityDate            : chr [1:1397] "3/25/2016" "3/26/2016" "3/27/2016" "3/28/2016" ...
 $ TotalSteps              : num [1:1397] 11004 17609 12736 13231 12041 ...
 $ TotalDistance           : num [1:1397] 7.11 11.55 8.53 8.93 7.85 ...
 $ TrackerDistance         : num [1:1397] 7.11 11.55 8.53 8.93 7.85 ...
 $ LoggedActivitiesDistance: num [1:1397] 0 0 0 0 0 0 0 0 0 0 ...
 $ VeryActiveDistance      : num [1:1397] 2.57 6.92 4.66 3.19 2.16 ...
 $ ModeratelyActiveDistance: num [1:1397] 0.46 0.73 0.16 0.79 1.09 ...
 $ LightActiveDistance     : num [1:1397] 4.07 3.91 3.71 4.95 4.61 ...
 $ SedentaryActiveDistance : num [1:1397] 0 0 0 0 0 0 0 0 0 0 ...
 $ VeryActiveMinutes       : num [1:1397] 33 89 56 39 28 30 33 47 40 15 ...
 $ FairlyActiveMinutes     : num [1:1397] 12 17 5 20 28 13 12 21 11 30 ...
 $ LightlyActiveMinutes    : num [1:1397] 205 274 268 224 243 223 239 200 244 314 ...
 $ SedentaryMinutes        : num [1:1397] 804 588 605 1080 763 ...
 $ Calories                : num [1:1397] 1819 2154 1944 1932 1886 ...
 - attr(*, "spec")=
  .. cols(
  ..   Id = col_double(),
  ..   ActivityDate = col_character(),
  ..   TotalSteps = col_double()[39m,
  ..   TotalDistance = col_double(),
  ..   TrackerDistance = col_double(),
  ..   LoggedActivitiesDistance = col_double(),
  ..   VeryActiveDistance = col_double(),
  ..   ModeratelyActiveDistance = col_double(),
  ..   LightActiveDistance = col_double(),
  ..   SedentaryActiveDistance = col_double(),
  ..   VeryActiveMinutes = col_double(),
  ..   FairlyActiveMinutes = col_double(),
  ..   LightlyActiveMinutes = col_double(),
  ..   SedentaryMinutes = col_double(),
  ..   Calories = col_double()
  .. )
"","      Id"," ActivityDate","  TotalSteps","TotalDistance","TrackerDistance","LoggedActivitiesDistance","VeryActiveDistance","ModeratelyActiveDistance","LightActiveDistance","SedentaryActiveDistance","VeryActiveMinutes","FairlyActiveMinutes","LightlyActiveMinutes","SedentaryMinutes","   Calories"
"","Min.   :1.504e+09  ","Min.   :2016-03-12  ","Min.   :    0  ","Min.   : 0.000  ","Min.   : 0.000  ","Min.   :0.0000  ","Min.   : 0.000  ","Min.   :0.0000  ","Min.   : 0.000  ","Min.   :0.000000  ","Min.   :  0.00  ","Min.   :  0.0  ","Min.   :  0.0  ","Min.   :   0.0  ","Min.   :   0  "
"","1st Qu.:2.320e+09  ","1st Qu.:2016-04-09  ","1st Qu.: 3146  ","1st Qu.: 2.170  ","1st Qu.: 2.160  ","1st Qu.:0.0000  ","1st Qu.: 0.000  ","1st Qu.:0.0000  ","1st Qu.: 1.610  ","1st Qu.:0.000000  ","1st Qu.:  0.00  ","1st Qu.:  0.0  ","1st Qu.:111.0  ","1st Qu.: 729.0  ","1st Qu.:1799  "
"","Median :4.445e+09  ","Median :2016-04-19  ","Median : 6999  ","Median : 4.950  ","Median : 4.950  ","Median :0.0000  ","Median : 0.100  ","Median :0.2000  ","Median : 3.240  ","Median :0.000000  ","Median :  2.00  ","Median :  6.0  ","Median :195.0  ","Median :1057.0  ","Median :2114  "
"","Mean   :4.781e+09  ","Mean   :2016-04-19  ","Mean   : 7281  ","Mean   : 5.219  ","Mean   : 5.192  ","Mean   :0.1315  ","Mean   : 1.397  ","Mean   :0.5385  ","Mean   : 3.193  ","Mean   :0.001704  ","Mean   : 19.68  ","Mean   : 13.4  ","Mean   :185.4  ","Mean   : 992.5  ","Mean   :2266  "
"","3rd Qu.:6.962e+09  ","3rd Qu.:2016-04-30  ","3rd Qu.:10544  ","3rd Qu.: 7.500  ","3rd Qu.: 7.480  ","3rd Qu.:0.0000  ","3rd Qu.: 1.830  ","3rd Qu.:0.7700  ","3rd Qu.: 4.690  ","3rd Qu.:0.000000  ","3rd Qu.: 30.00  ","3rd Qu.: 18.0  ","3rd Qu.:262.0  ","3rd Qu.:1244.0  ","3rd Qu.:2770  "
"","Max.   :8.878e+09  ","Max.   :2016-05-12  ","Max.   :36019  ","Max.   :28.030  ","Max.   :28.030  ","Max.   :6.7271  ","Max.   :21.920  ","Max.   :6.4800  ","Max.   :12.510  ","Max.   :0.110000  ","Max.   :210.00  ","Max.   :660.0  ","Max.   :720.0  ","Max.   :1440.0  ","Max.   :4900  "

 - attr(*, "problems")=<externalptr> 
Saving 7 x 7 in image
Saving 7 x 7 in image
Saving 7 x 7 in image
Saving 7 x 7 in image
Session restored from your saved work on 2024-May-18 03:47:54 UTC (2 days ago)
> 

![distribution_of_daily_steps.png](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/c99a9386-61e8-489a-b864-3f26ec8e2383)

![steps_vs_sedentary_minutes.png](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/57a45fbc-548f-436f-b5df-285cf8ef67fb)

![trends_in_activity_over_time.png](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/2cbc91c6-73cb-4ea3-9291-e9cababb6f33)

![steps_vs_sedentary_minutes.png](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/4529b819-e6ad-4a83-9a36-5dd43848c2ca)

![average_steps_by_user.png](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/b7b1764b-2e4f-4e86-a571-9550c122e40e)

Act
Comprehensive Analysis and Insights from Fitbit Data and Visualizations

General Information
Number of Records (Id): The Id range from 1.504e+09 to 8.878e+09, indicating a large number of unique users.
Activity Date: Data ranges from March 12, 2016, to May 12, 2016.
Data Summary
Steps and Distance
Total Steps:

Min: 0 steps
1st Quartile: 3,146 steps
Median: 6,999 steps
Mean: 7,281 steps
3rd Quartile: 10,544 steps
Max: 36,019 steps
Total Distance (in miles):

Min: 0.000 miles
1st Quartile: 2.170 miles
Median: 4.950 miles
Mean: 5.219 miles
3rd Quartile: 7.500 miles
Max: 28.030 miles
Tracker Distance: Values closely match Total Distance.

Min: 0.000 miles
Max: 28.030 miles
Logged Activities Distance:

Min: 0.000 miles
Max: 28.030 miles
Activity Levels
Very Active Distance:

Min: 0.0000 miles
Max: 6.7271 miles
Mean: 0.1315 miles
Moderately Active Distance:

Min: 0.000 miles
Max: 21.920 miles
Mean: 1.397 miles
Light Active Distance:

Min: 0.0000 miles
Max: 6.4800 miles
Mean: 0.5385 miles
Sedentary Active Distance:

Min: 0.000 miles
Max: 12.510 miles
Mean: 3.193 miles
Minutes Spent in Activity
Very Active Minutes:

Min: 0 minutes
Max: 210 minutes
Mean: 19.68 minutes
Fairly Active Minutes:

Min: 0 minutes
Max: 660 minutes
Mean: 13.4 minutes
Lightly Active Minutes:

Min: 0 minutes
Max: 720 minutes
Mean: 185.4 minutes
Sedentary Minutes:

Min: 0 minutes
Max: 1440 minutes
Mean: 992.5 minutes
Calories Burned
Calories:

Min: 0 calories
1st Quartile: 1,799 calories
Median: 2,114 calories
Mean: 2,266 calories
3rd Quartile: 2,770 calories
Max: 4,900 calories
Visualization Analysis

Average Steps by User
File: average_steps_by_user.png

Analysis:
Heatmap showing average steps taken by each user.
Darker shades indicate higher average steps, while lighter shades indicate lower averages.
Users with the highest average steps are clustered towards the right side of the heatmap.
Trends in Activity Over Time
File: trends_in_activity_over_time.png

Analysis:
Line graph tracking activity levels (steps) over time.
General upward trend from mid-March to late April, indicating an increase in activity.
Fluctuations suggest variations in daily or weekly activity patterns.
Sharp drop at the end needs further investigation to determine if it's an anomaly or a trend.
Steps vs. Sedentary Minutes
File: steps_vs_sedentary_minutes.png

Analysis:
Scatter plot exploring the relationship between total steps and sedentary minutes.
Weak negative correlation observed; as steps increase, sedentary minutes tend to decrease.
Some users exhibit high sedentary minutes despite taking a moderate number of steps.
Distribution of Daily Steps
File: distribution_of_daily_steps.png

Analysis:
Histogram showing the distribution of daily steps across all users.
Right-skewed distribution, with most users taking fewer steps daily.
Peak around 5,000 steps, indicating that many users achieve this number daily.
Outliers with exceptionally high step counts indicate a small number of highly active users.
Interpretation
Activity Levels:

Wide range in daily steps, distance traveled, and calories burned.
Median values indicate moderate activity levels (Median Total Steps: 6,999).
High mean values for Lightly Active Minutes and Sedentary Minutes show significant light and sedentary activity.
Variability:

Significant variance between minimum and maximum values in Very Active Minutes and Fairly Active Minutes.
Indicates some users are very active, while others are not active at all.
Recommendations
Target Low-Activity Users:

Develop personalized interventions to motivate and support users with low average steps.
Use insights from the heatmap to identify and engage these users.
Promote Consistency:

Encourage users to maintain consistent activity levels.
Address fluctuations observed in activity levels over time.
Reduce Sedentary Time:

Implement strategies to reduce prolonged sedentary periods.
Focus on users who take moderate steps but have high sedentary minutes.
Encourage Moderate Activity:

Shift the step distribution towards a higher average.
Set achievable daily step goals and provide incentives.
Plan Implementation
User Interface Enhancements:

Simplify goal setting and tracking within the app.
Provide real-time feedback on activity progress.
Data-Driven Insights:

Generate weekly and monthly activity reports.
Develop customizable alerts for users to remind them to stay active.
Community and Support:

Encourage users to join groups or challenges.
Offer access to fitness experts for personalized advice.
Deliverables
Enhanced App Features:

Goal-setting and tracking enhancements.
Real-time activity alerts.
Detailed activity reports.
User Education:

Guides on effective activity logging.
Nutritional advice linked with caloric expenditure.
Community Engagement:

Launch community challenges and group activities.
Provide expert consultations.
Next Steps
Data Validation:

Ensure accuracy and completeness of activity data.
Address any discrepancies or gaps in the data.
User Feedback:

Gather feedback on current app features and desired improvements.
Conduct surveys or focus groups to understand user needs.
Feature Development:

Prioritize development based on user feedback and data analysis.
Test new features with a beta group before a full rollout.

Final Conclusion
The analysis of Fitbit data and visualizations reveals that while users are moderately active, there is significant room for improvement in their very active minutes and overall activity levels. By implementing enhanced goal-setting features, personalized recommendations, and fostering community engagement, Bellabeat can help users achieve better health outcomes. Continuous monitoring and feedback will ensure these initiatives are effective and well-received by users.


License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
I would like to thank Bellabeat for providing the opportunity to work on this case study, as well as the Kaggle community for the publicly available FitBit dataset used in this analysis.



