# 911-Calls-Data-Analysis-Capstone-Project
Exploratory Data Analysis of 911 Emergency Calls using Python.

[Project Overview](#project-overview)

[Dataset Description](#dataset-description)

[Tools used](#tools-used)

[Skills Demonstrated](#skills-demonstrated)

[Data Cleaning](#data-cleaning)

[Analysis Performed](#analysis-performed)

[Key Insight](#key-insight)

[Conclusion](#conclusion)

## Project Overview
This project analyzes 911 emergency call records to uncover patterns in emergency incidents. The analysis focuses on identifying the most common emergency categories, understanding call trends over time, and exploring how emergency calls vary by day, month, and hour. The project was completed using Python and various data analysis libraries.

## Dataset Description
The dataset contains records of 911 emergency calls, including information about the location, time of occurrence, and nature of the emergency.

| Column | Description |
|---------|-------------|
| lat | Latitude of the emergency location |
| lng | Longitude of the emergency location |
| desc | Detailed description of the emergency call |
| zip | Zip code of the incident location |
| title | Title/category of the emergency call |
| timeStamp | Date and time when the call was received (YYYY-MM-DD HH:MM:SS) |
| twp | Township where the incident occurred |
| addr | Address of the emergency |
| e | Dummy variable (always equal to 1) |

## Tools Used
- Python

- Pandas

- NumPy
  
- Matplotlib
  
- Seaborn

- Jupyter Notebook

## Skills Demonstrated
Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, Feature Engineering, and Insight Generation using Python

## Data Cleaning

- Checked for missing values.

- Converted timestamp data to datetime format.

- Extracted month, day, and hour from the timestamp column.

- Created new features for time-based analysis.

## Analysis Performed

- Identified the most common emergency call categories.

- Analyzed call volume by month.

- Examined call distribution by day of the week.

- Investigated peak hours for emergency calls.

- Created visualizations to highlight trends and patterns.

## Key Insights
EMS (Emergency Medical Services) recorded the highest number of 911 emergency calls, making it the most common reason for emergency requests.
Traffic-related incidents accounted for the second-highest number of emergency calls.
Fire emergencies recorded the lowest number of calls among the three major categories.
The distribution of calls indicates that medical emergencies occur more frequently than traffic and fire-related incidents.
Emergency response agencies may need to allocate more resources to EMS operations due to the significantly higher call volume.

<img width="867" height="675" alt="911 Calls image" src="https://github.com/user-attachments/assets/bbc9c07c-64ab-43cb-95d1-19128deff12a" />


## Conclusion

Based on the analysis of 911 emergency call records, EMS accounted for the largest proportion of emergency calls, followed by Traffic incidents and Fire emergencies. These findings suggest that medical emergencies are the primary driver of emergency service demand. Understanding these patterns can help emergency response agencies make informed decisions regarding resource allocation, staffing, and operational planning. This project demonstrates the use of Python for data cleaning, exploratory data analysis, feature engineering, and data visualization.

