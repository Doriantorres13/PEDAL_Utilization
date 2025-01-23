Summary of SQL Analysis for PEDAL Utilization Data (2023-2024)

This project analyzes the utilization data of spin classes at PEDAL between 2023 and 2024. The SQL queries were designed to answer specific business questions, and insights were visualized in the accompanying dashboard. Below are the key steps and queries used in this analysis:

1. Instructor Activity:
- Identified the top three instructors by the number of classes taught from 2023 to 2024.
2. Class Utilization:
- Determined the spin classes with the highest utilization in both 2023 and 2024.
- Focused on spin classes (ClassType = 'SPIN') for deeper insights.
3. Yearly Utilization Trends:
- Compared the average utilization of spin classes in 2023 and 2024.
- Calculated the percentage decrease in utilization year-over-year.
4. Day-Specific Trends:
- Analyzed the average utilization for each day of the week in 2023 and 2024.
- Sorted the data to align with the weekly calendar for better interpretation.
5. Attendance Analysis:
- Calculated the total number of check-ins for spin classes in 2023 and 2024.
- Computed the percentage increase in attendance from 2023 to 2024.
6. Data Preparation:
- Updated the ClassDayofWeek column to remove unnecessary whitespace and standardize data for analysis.
  
Key Insights
- Brooke Bell emerged as the top instructor, teaching the most classes.
- The top-utilized spin classes in 2023 and 2024 were identified, providing actionable data for scheduling.
- Average spin class utilization decreased by approximately 9.53% from 2023 to 2024.
- Weekend classes (Saturday and Sunday) consistently had the highest utilization across both years.
- The total number of check-ins increased significantly in 2024, despite the drop in average utilization.
  
File Structure
- SQL Queries: All queries used for analysis are documented and can be adapted for similar datasets.
- Dashboard: The visual dashboard (Utilization_Dashboard.png) provides a graphical summary of key metrics.
  
Future Steps
- Expand analysis to include other class types or demographic trends.
- Investigate reasons behind the drop in average utilization while attendance increased.
- Utilize this data for optimizing class schedules and instructor assignments.
