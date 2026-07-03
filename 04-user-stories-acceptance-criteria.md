# User Stories and Acceptance Criteria: SaaS Churn Dashboard

## Purpose
This document converts the product backlog into user stories and acceptance criteria for Agile delivery in Jira.

---

## User Story 1: Overall Churn Rate

**As a** Head of Customer Success,  
**I want** to view the overall customer churn rate,  
**so that** I can understand the scale of customer loss and track retention performance.

### Acceptance Criteria
- Churn rate is calculated using churned customers divided by total customers.
- The dashboard displays overall churn rate as a KPI card.
- The churn rate value is validated against SQL or Python output.
- The metric is clearly labelled and easy for non-technical stakeholders to understand.

---

## User Story 2: Churn by Customer Segment

**As a** Customer Success Manager,  
**I want** to view churn by industry, plan tier and acquisition source,  
**so that** I can identify high-risk customer groups and prioritise retention actions.

### Acceptance Criteria
- Dashboard includes churn breakdown by industry.
- Dashboard includes churn breakdown by plan tier.
- Dashboard includes churn breakdown by acquisition source.
- High-risk segments are visually clear.
- Filters allow stakeholders to explore customer groups.

---

## User Story 3: Revenue-at-Risk View

**As a** Revenue Operations Manager,  
**I want** to see monthly and annual revenue at risk,  
**so that** I can understand the financial impact of churn.

### Acceptance Criteria
- Monthly revenue at risk is calculated and displayed.
- Annual revenue at risk is calculated and displayed.
- Revenue-at-risk values are validated against source calculations.
- Dashboard shows revenue exposure by plan tier.
- Values are formatted clearly for business users.

---

## User Story 4: Executive Dashboard View

**As an** Executive Leadership stakeholder,  
**I want** a high-level dashboard view,  
**so that** I can quickly understand churn performance, revenue exposure and retention priorities.

### Acceptance Criteria
- Dashboard includes headline KPI cards.
- Dashboard includes churn and revenue-risk visuals.
- Dashboard avoids unnecessary technical detail.
- Key insights are written in business language.
- Dashboard can be explained in under five minutes.

---

## User Story 5: Product Usage Review

**As a** Product Manager,  
**I want** to review churn patterns alongside customer usage behaviour,  
**so that** I can identify whether low engagement may be linked to churn.

### Acceptance Criteria
- Usage-related data is reviewed during analysis.
- Low-engagement customer groups are identified where possible.
- Product-related churn insights are included in the recommendation summary.
- Findings are clearly separated from assumptions.

---

## User Story 6: Dashboard Filters

**As a** business stakeholder,  
**I want** interactive filters for customer segmentation,  
**so that** I can explore churn and revenue risk by different customer groups.

### Acceptance Criteria
- Dashboard includes relevant filters.
- Filters work across key dashboard visuals.
- Filter labels are clear.
- Filters do not break KPI calculations.
- Filtered views remain easy to interpret.

---

## User Story 7: Final Recommendations

**As a** senior stakeholder,  
**I want** clear retention recommendations,  
**so that** the analysis can support practical business decisions.

### Acceptance Criteria
- Recommendations are based on churn and revenue-at-risk findings.
- Recommendations are written in business language.
- Recommendations identify priority customer segments.
- Recommendations avoid unsupported claims.
- Final summary links insights to stakeholder needs.

---

## User Story 8: Metric Validation

**As a** BI or Data Analyst,  
**I want** dashboard metrics to be validated,  
**so that** stakeholders can trust the final output.

### Acceptance Criteria
- Churn rate is checked against source calculations.
- Revenue-at-risk metrics are checked against source calculations.
- Data quality issues are documented.
- Any assumptions are clearly stated.
- Final dashboard numbers are consistent with the analysis outputs.

---

## Summary
These user stories support the Agile delivery of a stakeholder-focused SaaS churn dashboard. Each story connects a stakeholder need to a clear business outcome and measurable acceptance criteria.
