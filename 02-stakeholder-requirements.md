# Stakeholder Requirements: SaaS Churn Dashboard

## Project Context
The SaaS business needs a dashboard that helps stakeholders understand customer churn, recurring revenue at risk and retention priorities. The dashboard should support decision-making for Customer Success, Revenue Operations, Product and Executive Leadership teams.

## Stakeholders

### Head of Customer Success
Needs visibility into which customer segments are most likely to churn so that the team can prioritise retention actions.

Key requirements:
- View overall customer churn rate
- Identify churn by industry, plan tier and acquisition source
- Understand which customer groups need retention focus
- Track churn patterns in a simple executive view

### Revenue Operations Manager
Needs to understand the financial impact of churn and where recurring revenue is most exposed.

Key requirements:
- View monthly revenue at risk
- View annual revenue at risk
- Segment revenue exposure by plan tier
- Identify which customer groups contribute the highest financial risk

### Product Manager
Needs to understand whether churn may be linked to product usage and customer engagement.

Key requirements:
- Review churn patterns alongside feature usage
- Identify low-engagement customer groups
- Understand whether specific customer segments may require product or onboarding improvements

### Executive Leadership Team
Needs a high-level dashboard that summarises churn performance, revenue exposure and retention priorities.

Key requirements:
- View headline KPIs clearly
- Understand the scale of churn and revenue risk
- Identify top retention priorities
- Access clear business recommendations without needing technical explanation

### Data / BI Team
Needs clear definitions and acceptance criteria to build and validate the dashboard correctly.

Key requirements:
- Define churn rate calculation
- Define monthly revenue at risk calculation
- Define annual revenue at risk calculation
- Validate filters and dashboard outputs
- Ensure dashboard metrics are consistent and explainable

## Functional Requirements

| Requirement ID | Requirement |
|---|---|
| FR-01 | The dashboard should show overall churn rate. |
| FR-02 | The dashboard should show churn by industry. |
| FR-03 | The dashboard should show churn by acquisition source. |
| FR-04 | The dashboard should show churn by plan tier. |
| FR-05 | The dashboard should calculate monthly revenue at risk. |
| FR-06 | The dashboard should calculate annual revenue at risk. |
| FR-07 | The dashboard should show revenue at risk by plan tier. |
| FR-08 | The dashboard should include filters for customer segment analysis. |
| FR-09 | The dashboard should include clear KPI cards for executive review. |
| FR-10 | The dashboard should include final business recommendations. |

## Non-Functional Requirements

| Requirement ID | Requirement |
|---|---|
| NFR-01 | Dashboard visuals should be simple, executive-friendly and easy to interpret. |
| NFR-02 | Metrics should be clearly defined and validated before dashboard delivery. |
| NFR-03 | Dashboard should avoid unnecessary technical complexity for business users. |
| NFR-04 | Insights should be written in business language. |
| NFR-05 | The final output should be suitable for stakeholder presentation. |

## Success Criteria

The project will be considered successful if:
- Stakeholders can clearly understand churn performance.
- Revenue exposure is quantified through MRR and ARR risk.
- High-risk customer segments are visible.
- Dashboard outputs support retention prioritisation.
- The final dashboard can be explained clearly to non-technical stakeholders.
