# Predictive-Analysis-of-Eye-Health-Risk-Factors-Across-Demographics
## Project Overview
The objective of this analysis is to identify and understand key risk factors associated with eye health conditions across various demographic groups. By analyzing how factors like age, race, and lifestyle contribute to the likelihood of eye health issues, one can provide predictive insights and recommendations.
## Analysis Approach
1. **Data Exploration and Preparation**
   - **Identify Relevant Fields:** These were identified as Age, Gender, RaceEthnicity, RiskFactor, Data_Value, and Sample_Size.
   - **Data Cleaning:** To ensure that all demographic and risk factor data points were complete. Where there were null values, i decided to replace these with the median values of the respective columns within Power Query. I also categorized age groups for more granularity in the form: 18–39, 40–64, etc.
2. **Risk Factor Analysis**
   - **Objective:** Identify which risk factors have the highest correlation with poor eye health outcomes. It is worth noting that for the sake of visualization, i incorporated the risk factors as a slicer and used the data value column as row values in the pivot tables generated for each of the demographic points.
   - **Actions:**
I used Pivot Tables to segment the data by RiskFactor, Age, Gender, and RaceEthnicity.
Calculated the average Data_Value for each risk factor to see which ones have the highest prevalence.
3. **Demographic Predictive Patterns**
   - **Objective**: Examine patterns by age, gender, and ethnicity to identify groups with a higher likelihood of eye health issues.
   - **Actions**:
Create a Pivot Table for each demographic, showing average Data_Value across age, gender, and race.
Calculate the prevalence rates within each demographic to identify higher-risk groups.
Visualize findings with bar charts for each demographic category, making it easy to spot which groups have a higher occurrence of eye health problems.
4.  **Confidence Interval Analysis**
    - **Objective**: Assess the reliability of predictions within each risk group.
    - **Actions**:
Calculate the average Low_Confidence_Limit and High_Confidence_Limit. These appear as interactive KPI's in the final dashboard, bearing in mind that the various risk factors appear as a slicer to which all the pivot charts in the dashboard respond respectively.
5. **Interactive Dashboard and Insights**
    - **Objective**: Summarize insights in an Excel dashboard with interactive elements.
    - **Actions**:
Set up slicers for filtering by risk factors, age, gender, and race on a Dashboard sheet.
Include charts and tables showing risk factor prevalence and demographic patterns.
Add a summary of key findings and recommendations, e.g., groups that may benefit from targeted eye health interventions.
The dashboard is shown below:

														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
														
![image](https://github.com/user-attachments/assets/7192c54e-a8e7-4867-9ea4-1d6ef82cf4c8)

**Key Deliverables**
  - **Pivot Tables**: summarizing prevalence by risk factor and demographic.
  - **Charts and Visualizations**: for risk factors and demographic trends.
  - **Interactive Dashboard with slicers**: to view data by various categories.
Summary Sheet with insights, risk factors, and demographic trends.

## Summary/Insights
**Risk Factors by Gender**:

Across all risk factors (Diabetes, Hypertension, Smoking, and Others), the average data value percentage is relatively close for each gender.
Males have a slightly higher average data value percentage across most conditions, suggesting that males may have a marginally higher prevalence or risk factor for these health issues.
Risk Factors by Age:

The data indicates that the prevalence of eye health issues or related risk factors increases with age, peaking in the "Above 85" category (21.07%) and the "Unknown" age category (22.14%).
Younger age groups, such as "18-39" (16.87%) and "40-64" (18.12%), have lower average data values, suggesting fewer vision health issues or risk factors among younger individuals.
Risk Factors by Ethnicity:

Among ethnic groups, "North American Native" has the highest average data value percentage (20.66%), followed by "Asian" (19.32%). This suggests a potentially higher prevalence or risk among these groups.
"White, non-Hispanic" has the lowest average percentage (17.16%), indicating relatively fewer vision-related issues or risk factors among this group.
Confidence Limits:

The average of the low confidence limit is 11.26%, and the high confidence limit is 14.76%, which gives a range for the possible values, suggesting some variability in the data.



