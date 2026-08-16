# Document-Controller-Dashboard-Power-BI

# 1. Project Overview

The Document Controller Dashboard is an interactive Power BI dashboard designed to monitor, analyze, and track project documentation activities.

The dashboard provides management and document control teams with a centralized view of:

Total documents<br>
Document approval status<br>
Document submissions<br>
Documents under review<br>
Rejected documents<br>
Overdue documents<br>
Project-wise document performance<br>
Discipline-wise document distribution<br>
Monthly submission and approval trends<br>
KPI performance<br>
Document aging analysis<br>

The dashboard is designed to support document control monitoring, management reporting, performance tracking, and timely decision-making.

# 2. Dashboard Objectives

The main objectives of this dashboard are:

Monitor the overall document status across projects.<br>
Track document submissions and approvals.<br>
Identify rejected and overdue documents.<br>
Analyze documentation performance by project.<br>
Analyze document distribution by discipline.<br>
Monitor monthly submission and approval trends.<br>
Track document control KPIs against predefined targets.<br>
Identify aging and delayed documents.<br>
Provide management with an interactive executive summary.<br>
Support document controllers in identifying areas requiring corrective action.<br>


# 3. Dashboard Pages

The Power BI report contains the following pages:

Page 1 – Executive Summary

The Executive Summary provides a high-level overview of the document control performance.

Key Cards<br>
Total Documents<br>
Approved Documents<br>
Submitted Documents<br>
Documents Under Review<br>
Rejected Documents<br>
Overdue Documents<br>
Visualizations<br>
Status Distribution<br>
Monthly Submissions Trend<br>
Project Wise Documents<br>
Discipline Wise Documents<br>
Filters<br>
Project Name<br>
Client Name<br>
Discipline<br>

This page is mainly designed for Project Managers, Document Control Managers, and Management.

# 4. Project Wise Status

This page provides detailed analysis of document status by project.

Visualizations<br>
Document Status by Project<br>
Monthly Approval Trend<br>
Project Summary Table<br>
Monthly Submission Trend<br>
Project Status Categories<br>
Approved<br>
Submitted<br>
Under Review<br>
Rejected<br>
Overdue<br>
Project Summary<br>

The summary table provides project-wise information such as:

Project Name<br>
Total Documents<br>
Approved Documents<br>
Submitted Documents<br>
Documents Under Review<br>
Rejected Documents<br>
Overdue Documents<br>

This page helps identify which projects are performing well and which projects require attention.

# 5. Discipline Wise Analysis

This page analyzes documentation based on engineering and project disciplines.

Disciplines Covered<br>
Civil<br>
Electrical<br>
ELV<br>
Mechanical<br>
HSE<br>
QA/QC<br>
Visualizations<br>
Document Distribution by Discipline<br>
Discipline-wise Document Count<br>
Project-wise Status Details<br>
Detailed Table<br>

The detailed table includes:

Discipline<br>
Project Name<br>
Approved Documents<br>
Month<br>
Under Review<br>
Rejected Documents<br>
Overdue Documents<br>
Approval %<br>
Rejection %<br>
Overdue %<br>

This page helps identify documentation performance at the discipline level.

# 6. KPI Monitoring

The KPI Monitoring page tracks document control performance against defined targets.

KPIs<br>
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

Visualizations<br>
KPI Scorecard<br>
Monthly KPI Trend<br>
KPI Actual vs Target<br>

The KPI page allows management to quickly identify whether document control performance is meeting the required targets.

# 7. Aging Analysis

The Aging Analysis page identifies documents based on their aging period.

Aging Buckets<br>
0–30 Days<br>
31–60 Days<br>
61–90 Days<br>
91–120 Days<br>
121–180 Days<br>
180+ Days<br>
Visualizations<br>
Aging Bucket Analysis<br>
Aging Distribution<br>
Overdue Document Details<br>
Detailed Information<br>

The overdue document table contains:

Document Number<br>
Document Title<br>
Project Name<br>
Discipline<br>
Responsible Engineer<br>
Aging Days<br>
Status<br>

This page helps document controllers prioritize old and overdue documents.

# 8. Interactive Filters

The dashboard contains interactive slicers to allow users to analyze specific data.

Available Filters<br>
Project<br>
Client<br>
Discipline<br>
Month<br>
Status<br>

Users can select one or multiple values to dynamically update the dashboard visuals.

# 9. Key Data Fields

The dashboard is based on document control information such as:

Field	Description<br>
Document Number	Unique document identification number<br>
Document Title	Name/title of the document<br>
Project Name	Project associated with the document<br>
Client Name	Client associated with the project<br>
Discipline	Engineering/project discipline<br>
Status	Current document status<br>
Month	Submission/approval month<br>
Responsible Engineer	Person responsible for the document<br>
Submission Date	Date document was submitted<br>
Approval Date	Date document was approved<br>
Rejection Date	Date document was rejected<br>
Aging Days	Number of days the document has remained pending/overdue<br>

# 10. Document Status Definitions

Status	Description<br>
Approved	Document has successfully completed the approval process<br>
Submitted	Document has been submitted for review<br>
Under Review	Document is currently being reviewed<br>
Rejected	Document has been rejected and requires correction/resubmission<br>
Overdue	Document has exceeded the required processing/submission period<br>

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

Microsoft Power BI Desktop<br>
Power Query – Data cleaning and transformation<br>
DAX – Measures and KPI calculations<br>
Power BI Visualizations – Charts, tables, cards and slicers<br>

# 13. Data Preparation

The data preparation process includes:

Importing the document control dataset.<br>
Removing duplicate records.<br>
Handling blank/null values.<br>
Standardizing project and discipline names.<br>
Formatting date fields.<br>
Creating document status categories.<br>
Calculating document aging.<br>
Creating KPI-related fields.<br>
Creating DAX measures.<br>
Building relationships between relevant tables, where applicable.<br>

# 14. Dashboard Navigation

The dashboard can be navigated through the left-side menu:

Executive Summary → Project Wise Status → Discipline Analysis → KPI Monitoring → Aging Analysis

Each page provides a different level of analysis, starting from management-level summary and moving toward detailed document-level information.

# 15. Intended Users

This dashboard is suitable for:

Document Controllers<br>
Document Control Managers<br>
Project Managers<br>
Planning Engineers<br>
Project Controls Teams<br>
Engineering Managers<br>
QA/QC Teams<br>
Management<br>

# 16. Business Benefits

The dashboard provides the following benefits:

Centralized document control monitoring<br>
Faster identification of overdue documents<br>
Improved visibility of approval performance<br>
Project-wise performance comparison<br>
Discipline-wise documentation analysis<br>
Better monitoring of document aging<br>
KPI-based performance measurement<br>
Improved management reporting<br>
Reduced manual reporting effort<br>
Data-driven decision making<br>

# 17. Assumptions

The following assumptions are considered for dashboard reporting:

Each document has a unique document number.<br>
Document status is maintained consistently.<br>
Submission and approval dates are available where applicable.<br>
Aging is calculated based on the relevant document processing date.<br>
KPI targets are predefined and can be modified according to project requirements.<br>
Dashboard results depend on the accuracy and completeness of the source data.<br>

# 18. How to Use the Dashboard

Open the Power BI report.<br>
Select the required dashboard page.<br>
Use the slicers at the top of the page.<br>
Select Project, Client, Discipline, Month, or Status.<br>
Review the KPI cards.<br>
Analyze the charts and trends.<br>
Use detailed tables to identify individual documents.<br>
Use the Aging Analysis page to prioritize overdue documents.<br>
Clear filters to return to the overall dashboard view.<br>

# 19. Conclusion

The Document Controller Dashboard provides an integrated and interactive solution for monitoring project documentation performance.

It combines document status tracking, project-wise analysis, discipline-wise analysis, KPI monitoring, trend analysis, and aging analysis into a single Power BI reporting solution.

The dashboard enables document control teams and project management to identify delays, monitor performance, track approvals, and take timely corrective actions.

## Project Deliverable

Project: Document Controller Dashboard<br>
Tool: Microsoft Power BI<br>
Domain: Document Control / Project Controls<br>
Dashboard Type: Interactive Management Dashboard<br>
Primary Purpose: Document Status, KPI, Trend and Aging Monitoring<br>
