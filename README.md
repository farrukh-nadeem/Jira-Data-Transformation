# Jira-Data-Transformation
Built ETL pipelines + Looker Studio dashboards to replace manual tracking,  enabling data-driven sprint management

**1. Project Overview**
     
     1. Tools Used: Jira, Google Sheets, Looker Studio
     2. Duration: 4 months (Oct 2023 - Jan 2024)
     3. My Role: Project Manager & Data Solutions Architect
     4. Key Outcome: Eliminated 8+ hours/week of manual reporting; enabled real-time risk identification

**2. Problem Statement**
 
     1. Inconsistent Processes: 5 teams using Jira differently - cross-module dependencies were untracked
     2. Manual Workarounds: Managers compiled progress reports in Google sheets manually, wasting 2+ hours daily
     3. Blind Decision-Making: No centralized data - bug/rework trends invisible until crises
     4. Communication Chaos: Verbal syncs needed for basic queries ("Is Feature X blocked?")

**3. Solution**

    1. For Data Extraction I used Jira Cloud for sheets extension to pull tickets (status, assignee, ticket history etc.,)
    2. To establish Data Pipeline I automated daily sync to Google Sheets using Jira Cloud for sheets extension
    3. Defined Taxonomy Design and created unified ticket labels/stages (e.g., "Blocked/Needs Rework") through Jira Scheme Designer
    4. Designed Dashboards to build 3 real-time reports: Sprint Health, Workflow efficiency, Strengths & Weaknesses using Looker Studio

**4. Business Impact**
 
Measurable Results & Qualitative Feedback
 
    1. Time Saved: Reduced manual report generation from 10 hrs/week to 2 hrs/week (Calculated via team self-reporting)
    2. Risk Detection: Identified ~13% of Institution Team's tickets were rework - previously undocumented
    3. Error Reduction: Eliminated dependency conflicts during ongoing sprints
 
Qualitative Feedback:

 "Your dashboards finally showed why we miss deadlines, now we fix 
bottlenecks regularly." - Hadil AL-Sewaiee - Testing Team Lead at Fresh Futures

**5. Lessons Learned**
 
+What Worked Well:

    1. Standardized taxonomy made cross-team tickets discoverable
    2. Adding components and feature types to tickets along with time spent helped identify key strengths and weaknesses of developers.

!What I'd Improve Next Time:
 
    1. Add automated alerts when critical tickets stall
    2. Add python script for data transformation to eliminate the remaining need for manual intervention.

Thank You!

Thank you for your time and attention today. We hope this presentation offered valuable insights into our Agile transformation 
journey and its positive impact.

 **Connect With Me**

 Name: Farrukh Nadeem |
 Email: fnadeem485@gmail.com |
 Contact No: +92 332 0378871
 
 LinkedIn: https://www.linkedin.com/in/farrukh-nadeem-999b931bb/
