# Advanced-Visual-Analytics

**Overview**
This project is part of the Visual Analytics course, aimed at analyzing student video engagement data using Alteryx and Tableau. The objective is to clean and prepare the dataset in Alteryx, and then create insightful dashboards in Tableau to help instructors and course managers understand viewing behaviors and session performance.

**Files**
1. Q2Exam.yxmd (Alteryx Workflow)
Purpose: Cleans, transforms, and reshapes raw video engagement data.

**Key Operations:**

Converted timestamps

Filtered relevant session types

Split and reorganized data columns

Created new attributes (e.g., session type, minutes viewed)

Ensured tidy data structure compatible with Tableau

2. FinalDashboardingQ2.twbx (Tableau Packaged Workbook)
Purpose: Visualizes student engagement metrics across sessions, weekdays, and study programs.

**Dashboards Included:**

Completion Rate Analysis: Compares average completion rates by session type and weekday.

Viewing Time Patterns: Analyzes minutes viewed per session, study program, and session type.

Engagement Trends: Shows weekly engagement trends, including pre-recorded vs. live sessions.

Session-Level Insights: Highlights performance of individual sessions.

**How to Use**
Open the Alteryx Workflow:

File: Q2Exam.yxmd

Ensure input data paths are correctly set if working on a local machine.

Run the workflow to generate cleaned output data.

Open the Tableau Workbook:

File: FinalDashboardingQ2.twbx

Review the interactive dashboards and apply filters (e.g., weekday, study program) to explore trends.

The workbook is pre-loaded with cleaned data and ready for exploration.

**Insights Gained**
Lower video completion rates were observed for pre-recorded sessions.

Viewing patterns vary significantly across weekdays and study programs.

Shorter video lengths often correlated with higher completion.

Some sessions had particularly high or low engagement, highlighting areas for pedagogical improvement.

**Tools Used**
Alteryx Designer (for data wrangling and transformation)

Tableau Desktop (for data visualization and dashboarding)
