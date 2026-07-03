# Epics and Product Backlog: SaaS Churn Dashboard

## Project Overview
This document converts stakeholder requirements into Agile epics and backlog items for the SaaS churn and revenue-at-risk dashboard. The backlog is structured to support Scrum-based delivery using Jira.

## Epics

| Epic ID | Epic Name | Purpose |
|---|---|---|
| EPIC-01 | Requirements Discovery | Understand stakeholder needs, define metrics and confirm dashboard scope. |
| EPIC-02 | Data Preparation | Prepare customer, subscription, usage, support and churn datasets for analysis. |
| EPIC-03 | Churn Analysis | Analyse churn rate and identify high-risk customer segments. |
| EPIC-04 | Revenue-at-Risk Analysis | Quantify monthly and annual recurring revenue exposure from churn. |
| EPIC-05 | Dashboard Development | Build an executive Power BI dashboard for stakeholder decision-making. |
| EPIC-06 | Testing and Validation | Validate dashboard metrics, filters and outputs before final delivery. |
| EPIC-07 | Final Delivery and Recommendations | Summarise findings, recommendations and delivery outcomes. |

## Product Backlog

| Backlog ID | Epic | User Story / Task | Priority |
|---|---|---|---|
| PB-01 | Requirements Discovery | Identify key stakeholders and document dashboard requirements. | High |
| PB-02 | Requirements Discovery | Define churn rate, monthly revenue at risk and annual revenue at risk. | High |
| PB-03 | Requirements Discovery | Confirm dashboard success criteria and business questions. | High |
| PB-04 | Data Preparation | Review available SaaS datasets and understand table relationships. | High |
| PB-05 | Data Preparation | Clean customer, subscription, usage, support and churn data. | High |
| PB-06 | Data Preparation | Validate missing values, duplicates and data types. | Medium |
| PB-07 | Churn Analysis | Calculate overall customer churn rate. | High |
| PB-08 | Churn Analysis | Analyse churn by industry, plan tier and acquisition source. | High |
| PB-09 | Churn Analysis | Identify highest-risk churn segments. | High |
| PB-10 | Revenue-at-Risk Analysis | Calculate monthly revenue at risk. | High |
| PB-11 | Revenue-at-Risk Analysis | Calculate annual revenue at risk. | High |
| PB-12 | Revenue-at-Risk Analysis | Analyse revenue exposure by plan tier. | High |
| PB-13 | Dashboard Development | Design dashboard layout and KPI structure. | High |
| PB-14 | Dashboard Development | Build Power BI visuals for churn and revenue risk. | High |
| PB-15 | Dashboard Development | Add filters for stakeholder segment analysis. | Medium |
| PB-16 | Testing and Validation | Validate KPI calculations against SQL/Python outputs. | High |
| PB-17 | Testing and Validation | Review dashboard usability and business clarity. | Medium |
| PB-18 | Final Delivery and Recommendations | Write final business recommendations and delivery summary. | High |
| PB-19 | Final Delivery and Recommendations | Document sprint review and retrospective notes. | Medium |

## Backlog Prioritisation Logic
High-priority items are required for the dashboard to answer the core business questions around churn, revenue exposure and retention priorities. Medium-priority items improve usability, documentation and stakeholder communication but are not blocking items for the first usable dashboard release.

## Definition of Ready
A backlog item is ready for sprint planning when:
- The objective is clear.
- The related stakeholder requirement is understood.
- The expected output is defined.
- Any data or dependency required is available.
- Acceptance criteria can be written.

## Definition of Done
A backlog item is complete when:
- The task output has been produced.
- Calculations or outputs have been checked.
- The result supports the dashboard or delivery documentation.
- The output can be explained in business language.
- Any required evidence is saved in the project repository.
