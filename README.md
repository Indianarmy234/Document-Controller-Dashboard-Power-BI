# Document-Controller-Dashboard-Power-BI

# 1. Project Overview

The Document Controller Dashboard is an interactive Power BI dashboard designed to monitor, analyze, and track project documentation activities.

The dashboard provides management and document control teams with a centralized view of:

Total documents
Document approval status
Document submissions
Documents under review
Rejected documents
Overdue documents
Project-wise document performance
Discipline-wise document distribution
Monthly submission and approval trends
KPI performance
Document aging analysis

The dashboard is designed to support document control monitoring, management reporting, performance tracking, and timely decision-making.

# 2. Dashboard Objectives

The main objectives of this dashboard are:

Monitor the overall document status across projects.
Track document submissions and approvals.
Identify rejected and overdue documents.
Analyze documentation performance by project.
Analyze document distribution by discipline.
Monitor monthly submission and approval trends.
Track document control KPIs against predefined targets.
Identify aging and delayed documents.
Provide management with an interactive executive summary.
Support document controllers in identifying areas requiring corrective action.


# 3. Dashboard Pages

The Power BI report contains the following pages:

Page 1 – Executive Summary

The Executive Summary provides a high-level overview of the document control performance.

Key Cards
Total Documents
Approved Documents
Submitted Documents
Documents Under Review
Rejected Documents
Overdue Documents
Visualizations
Status Distribution
Monthly Submissions Trend
Project Wise Documents
Discipline Wise Documents
Filters
Project Name
Client Name
Discipline

This page is mainly designed for Project Managers, Document Control Managers, and Management.

# 4. Project Wise Status

This page provides detailed analysis of document status by project.

Visualizations
Document Status by Project
Monthly Approval Trend
Project Summary Table
Monthly Submission Trend
Project Status Categories
Approved
Submitted
Under Review
Rejected
Overdue
Project Summary

The summary table provides project-wise information such as:

Project Name
Total Documents
Approved Documents
Submitted Documents
Documents Under Review
Rejected Documents
Overdue Documents

This page helps identify which projects are performing well and which projects require attention.

# 5. Discipline Wise Analysis

This page analyzes documentation based on engineering and project disciplines.

Disciplines Covered
Civil
Electrical
ELV
Mechanical
HSE
QA/QC
Visualizations
Document Distribution by Discipline
Discipline-wise Document Count
Project-wise Status Details
Detailed Table

The detailed table includes:

Discipline
Project Name
Approved Documents
Month
Under Review
Rejected Documents
Overdue Documents
Approval %
Rejection %
Overdue %

This page helps identify documentation performance at the discipline level.

# 6. KPI Monitoring

The KPI Monitoring page tracks document control performance against defined targets.

KPIs
1. On-Time Submission

Measures whether documents are submitted within the required timeframe.

Target: 95%

2. Approval Success Rate

Measures the percentage of submitted documents successfully approved.

Target: 90%

3. Document Accuracy

Measures the accuracy and quality of submitted documentation.

Target: 98%

4. Document Update Compliance

Measures whether required document updates are completed.

Target: 100%

5. Audit Compliance

Measures compliance with document control and audit requirements.

Target: 100%

6. Overdue Documents

Measures the level of overdue documentation.

Target: 5% or lower

Visualizations
KPI Scorecard
Monthly KPI Trend
KPI Actual vs Target

The KPI page allows management to quickly identify whether document control performance is meeting the required targets.

# 7. Aging Analysis

The Aging Analysis page identifies documents based on their aging period.

Aging Buckets
0–30 Days
31–60 Days
61–90 Days
91–120 Days
121–180 Days
180+ Days
Visualizations
Aging Bucket Analysis
Aging Distribution
Overdue Document Details
Detailed Information

The overdue document table contains:

Document Number
Document Title
Project Name
Discipline
Responsible Engineer
Aging Days
Status

This page helps document controllers prioritize old and overdue documents.

# 8. Interactive Filters

The dashboard contains interactive slicers to allow users to analyze specific data.

Available Filters
Project
Client
Discipline
Month
Status

Users can select one or multiple values to dynamically update the dashboard visuals.

# 9. Key Data Fields

The dashboard is based on document control information such as:

Field	Description
Document Number	Unique document identification number
Document Title	Name/title of the document
Project Name	Project associated with the document
Client Name	Client associated with the project
Discipline	Engineering/project discipline
Status	Current document status
Month	Submission/approval month
Responsible Engineer	Person responsible for the document
Submission Date	Date document was submitted
Approval Date	Date document was approved
Rejection Date	Date document was rejected
Aging Days	Number of days the document has remained pending/overdue

# 10. Document Status Definitions

Status	Description
Approved	Document has successfully completed the approval process
Submitted	Document has been submitted for review
Under Review	Document is currently being reviewed
Rejected	Document has been rejected and requires correction/resubmission
Overdue	Document has exceeded the required processing/submission period

# 11. Important Calculations

The dashboard uses Power BI measures/calculations to calculate document control performance.

Typical calculations include:

Total Documents

Total number of documents available in the selected filter context.

Approval %

Percentage of approved documents compared with total/submitted documents.

Rejection %

Percentage of rejected documents compared with applicable documents.

Overdue %

Percentage of overdue documents compared with total documents.

Aging Days

Number of days between the relevant document date and the current/reporting date.

KPI Variance

Difference between the actual KPI value and the predefined target.

# 12. Technology Used

Microsoft Power BI Desktop
Power Query – Data cleaning and transformation
DAX – Measures and KPI calculations
Power BI Visualizations – Charts, tables, cards and slicers

# 13. Data Preparation

The data preparation process includes:

Importing the document control dataset.
Removing duplicate records.
Handling blank/null values.
Standardizing project and discipline names.
Formatting date fields.
Creating document status categories.
Calculating document aging.
Creating KPI-related fields.
Creating DAX measures.
Building relationships between relevant tables, where applicable.

# 14. Dashboard Navigation

The dashboard can be navigated through the left-side menu:

Executive Summary → Project Wise Status → Discipline Analysis → KPI Monitoring → Aging Analysis

Each page provides a different level of analysis, starting from management-level summary and moving toward detailed document-level information.

# 15. Intended Users

This dashboard is suitable for:

Document Controllers
Document Control Managers
Project Managers
Planning Engineers
Project Controls Teams
Engineering Managers
QA/QC Teams
Management

# 16. Business Benefits

The dashboard provides the following benefits:

Centralized document control monitoring
Faster identification of overdue documents
Improved visibility of approval performance
Project-wise performance comparison
Discipline-wise documentation analysis
Better monitoring of document aging
KPI-based performance measurement
Improved management reporting
Reduced manual reporting effort
Data-driven decision making

# 17. Assumptions

The following assumptions are considered for dashboard reporting:

Each document has a unique document number.
Document status is maintained consistently.
Submission and approval dates are available where applicable.
Aging is calculated based on the relevant document processing date.
KPI targets are predefined and can be modified according to project requirements.
Dashboard results depend on the accuracy and completeness of the source data.

# 18. How to Use the Dashboard

Open the Power BI report.
Select the required dashboard page.
Use the slicers at the top of the page.
Select Project, Client, Discipline, Month, or Status.
Review the KPI cards.
Analyze the charts and trends.
Use detailed tables to identify individual documents.
Use the Aging Analysis page to prioritize overdue documents.
Clear filters to return to the overall dashboard view.

# 19. Conclusion

The Document Controller Dashboard provides an integrated and interactive solution for monitoring project documentation performance.

It combines document status tracking, project-wise analysis, discipline-wise analysis, KPI monitoring, trend analysis, and aging analysis into a single Power BI reporting solution.

The dashboard enables document control teams and project management to identify delays, monitor performance, track approvals, and take timely corrective actions.

## Project Deliverable

Project: Document Controller Dashboard
Tool: Microsoft Power BI
Domain: Document Control / Project Controls
Dashboard Type: Interactive Management Dashboard
Primary Purpose: Document Status, KPI, Trend and Aging Monitoring
