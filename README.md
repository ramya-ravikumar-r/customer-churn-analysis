# Customer Churn Analysis — Tableau Dashboard

Interactive Tableau dashboards that visualize customer churn trends, segment high-risk customers, and surface actionable retention strategies for business stakeholders.


# Problem Statement
Customer churn is one of the most expensive problems a business faces — acquiring a new customer costs 5–7× more than retaining an existing one. This project transforms raw churn data into an interactive visual story that enables business teams to identify who is churning, why, and where to intervene.
Business Question: Which customer segments are at highest risk of churning, and what patterns predict departure?

# Dataset
PropertyDetailDomainTelecom / Subscription BusinessKey FieldsCustomer ID, Tenure, Contract Type, Monthly Charges, Churn LabelAnalysis LevelCustomer-level with cohort segmentation

# Dashboard Pages
Page 1 — Executive Churn Overview

Overall Churn Rate KPI — headline metric at a glance
Churn by Contract Type — month-to-month vs. 1-year vs. 2-year
Churn by Tenure Cohort — when do customers leave?
Monthly Revenue Lost to Churn

Page 2 — High-Risk Segment Analysis

Churn Rate by Internet Service Type
Payment Method vs. Churn — electronic check customers churn most
Monthly Charges Distribution — churners vs. retained customers
Top 10% Highest-Risk Customer Profiles

Page 3 — Retention Opportunity Map

Churn probability heatmap by segment
Revenue at risk by customer cohort
Recommended intervention segments — where retention spend has highest ROI


# Key Insights
FindingBusiness ImplicationMonth-to-month contracts churn 3× more than 2-year contractsIncentivize annual contract upgradesCustomers with tenure < 12 months are highest riskTarget onboarding-phase retention programsElectronic check payers churn mostNudge toward auto-pay enrollmentHigh monthly charges + no tech support → high churnBundle tech support for premium-tier customers

# Tools Used
Tableau Desktop Calculated Fields LOD Expressions Dashboard Actions Filters & Parameters


# How to View

Download customer_churn_dashboard.twbx from the dashboard/ folder
Open in Tableau Desktop or Tableau Public
Use the filters on each page to explore by segment, region, or contract type


# Business Impact

Enables non-technical stakeholders to self-serve churn insights without SQL
Identifies the 3 highest-ROI customer segments for retention investment
Reduces time-to-insight from days (manual analysis) to seconds (dashboard)
