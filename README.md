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

```r
# Load necessary libraries
if (!requireNamespace("ggplot2", quietly = TRUE)) {
  install.packages("ggplot2")
}
if (!requireNamespace("dplyr", quietly = TRUE)) {
  install.packages("dplyr")
}
if (!requireNamespace("readr", quietly = TRUE)) {
  install.packages("readr")
}
library(ggplot2)
library(dplyr)
library(readr)

# Identify correct file paths
file1 <- "mturkfitbit_export_3.12.16-4.11.16/Fitabase Data 3.12.16-4.11.16/dailyActivity_merged.csv"
file2 <- "mturkfitbit_export_4.12.16-5.12.16/Fitabase Data 4.12.16-5.12.16/dailyActivity_merged.csv"

# Import the data
fitbit_data1 <- read_csv(file1)
fitbit_data2 <- read_csv(file2)

# Combine the data into a single dataframe
fitbit_data <- bind_rows(fitbit_data1, fitbit_data2)

# Data Cleaning and Organization
fitbit_data$ActivityDate <- as.Date(fitbit_data$ActivityDate, format="%m/%d/%Y")
fitbit_data <- na.omit(fitbit_data)
fitbit_data <- fitbit_data[!duplicated(fitbit_data), ]

# Save cleaned data to CSV
write.csv(fitbit_data, "cleaned_fitbit_data.csv", row.names = FALSE)

# Save summary statistics to CSV
summary_stats <- summary(fitbit_data)
write.csv(summary_stats, "summary_statistics.csv")

# Visualization 1: Bar Chart - Average Steps by User
ggplot(fitbit_data, aes(x = Id, y = TotalSteps)) +
  geom_bar(stat = "identity", fill = "skyblue") +
  labs(title = "Average Steps by User", x = "User ID", y = "Total Steps") +
  theme_minimal()

# Visualization 2: Line Chart - Daily Activity Over Time
ggplot(fitbit_data, aes(x = ActivityDate, y = TotalSteps, group = Id, color = Id)) +
  geom_line() +
  labs(title = "Daily Activity Over Time", x = "Date", y = "Total Steps") +
  theme_minimal()

# Visualization 3: Scatter Plot - Steps vs. Calories
ggplot(fitbit_data, aes(x = TotalSteps, y = Calories, color = Id)) +
  geom_point() +
  labs(title = "Steps vs. Calories", x = "Total Steps", y = "Calories Burned") +
  theme_minimal()


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
 - attr(*, "problems")=<externalptr> 
Saving 7 x 7 in image
Saving 7 x 7 in image
Saving 7 x 7 in image
Saving 7 x 7 in image
Session restored from your saved work on 2024-May-18 03:47:54 UTC (2 days ago)
> 

![file_show (1)](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/c99a9386-61e8-489a-b864-3f26ec8e2383)

![file_show (2)](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/57a45fbc-548f-436f-b5df-285cf8ef67fb)

![file_show (3)](https://github.com/LOLO-MKHWANAZI/Bellabeat-Data-Analysis-Case-Study/assets/163551783/2cbc91c6-73cb-4ea3-9291-e9cababb6f33)



Act
Recommendations
Based on the analysis, I will present actionable recommendations to Bellabeat's executive team, focusing on marketing strategies that leverage the insights gained from the data. These recommendations aim to enhance user engagement, improve product features, and ultimately drive business growth.

Key Tasks
Present Insights: I'll present the key findings and insights to the Bellabeat executive team, highlighting trends and patterns that are relevant to the business.
Develop Recommendations: I'll develop actionable recommendations based on the analysis, focusing on how Bellabeat can leverage the insights to improve its marketing strategy and product offerings.
Plan Implementation: I'll work with the team to develop a plan for implementing the recommendations, including timelines, resources, and key milestones.
Deliverable
A set of actionable recommendations and a detailed implementation plan.

Next Steps
Once the recommendations are approved, the team will move forward with implementing the changes and monitoring their impact on business performance.

Conclusion
The Bellabeat Data Analysis Case Study showcases the power of data analysis in driving business decisions and enhancing marketing strategies. By leveraging real-world data and analytical techniques, I have provided valuable insights and recommendations that can help Bellabeat achieve its growth objectives and continue to lead the wellness tech market.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
I would like to thank Bellabeat for providing the opportunity to work on this case study, as well as the Kaggle community for the publicly available FitBit dataset used in this analysis.



