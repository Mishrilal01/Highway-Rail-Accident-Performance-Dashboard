# Highway-Rail-Accident-Performance-Dashboard
📋 Project Overview
This project presents a comprehensive End-to-End Power BI Dashboard analyzing highway-rail grade crossing accidents from 1899 to 2025. The dashboard is designed to provide safety officials and transport analysts with deep insights into accident trends, fatality rates, and the environmental or behavioral factors that lead to collisions.

By synthesizing over 217K incidents, this tool transitions from high-level performance tracking to granular diagnostic analysis of why these accidents occur.

🏗️ Project Structure
The analysis is divided into two primary analytical views:

1. Performance Dashboard
Focuses on the "What" and "When."

KPIs: Total Accidents (217K), Total Fatalities (20K), Total Injuries (79K), and Fatality Rate (9.3%).

Time Intelligence: Annual accident and fatality trends showing a 90.6% reduction in deaths over the decades.

Operational Risk: Analysis of accidents by hour of the day, identifying peak risk windows.

Geospatial Mapping: Identification of accident hotspots across North America.

2. Root Cause Analysis
Focuses on the "Why" and "How."

Behavioral Analysis: Categorizing motorist actions (e.g., "Did Not Stop," "Went Around Gate").

Infrastructure Evaluation: Measuring the effectiveness of warning devices (Gates, Cantilever FLS, etc.).

Environmental Impact: Analyzing the correlation between weather states (Clear, Cloudy, Rain) and visibility obstructions.

📉 Key Findings & Insights
The Visibility Paradox: Clear weather accounts for the majority of accidents (144K), suggesting that driver overconfidence is a higher risk factor than poor weather.

Infrastructure Gap: 91.29% of accidents occurred at crossings already equipped with Gates, indicating that physical barriers are often bypassed by motorists.

Sightline Obstructions: Standing RR Equipment is the leading cause of visibility-related accidents (122K), far exceeding fog or topography.

Peak Risk Hours: Accidents peak between 10:00 AM and 4:00 PM, correlating with high-volume commercial and commuter traffic.

🛠️ Technical Stack & Methodology
Tool: Power BI Desktop

Data Transformation: Power Query (M) used for data cleaning, binning train speeds, and standardizing categorical variables.

Data Modeling: Star Schema implementation with specialized Dimension tables for Time, Geography, and Weather.

DAX Measures: Custom calculations for Fatality Rates, Year-over-Year (YoY) changes, and Percentages of Total.

🔗 Project Links
Live Dashboard (Google Drive):https://drive.google.com/drive/folders/1ppWIg8E3ChfDTXBbJUXUnzBWrGi1w1c2?usp=sharing

LinkedIn Post:https://www.linkedin.com/posts/mis-p_powerbi-dataanalytics-dashboarddesign-activity-7405651503702634496-ee-U?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEc1apEBMVz1IYns8QfgHAPxuGghQrvsgng

Data Source:https://drive.google.com/drive/folders/1ppWIg8E3ChfDTXBbJUXUnzBWrGi1w1c2?usp=sharing
📸 Dashboard Preview
Performance View
Root Cause Analysis View
💡 Recommendations
Infrastructure: Implement stricter regulations regarding "Standing Equipment" near active crossings to clear motorist sightlines.

Education: Shift public safety campaigns from "Weather Awareness" to "Gate Compliance" and "Daylight Vigilance."

Policy: Use the identified "Hotspots" map to prioritize the next phase of Grade Separation projects.

👤 Author
Mishrilal Parihar
LinkedIn Profile: www.linkedin.com/in/mis-p
