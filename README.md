# Credit-Risk-Analysis-Portfolio# Credit Risk & Portfolio Default Analysis

## Executive Summary
This project analyzes retail credit application data to identify primary drivers of loan default and optimize credit decisioning. By evaluating historical borrower behavior across high-risk segments, this analysis provides actionable underwriting recommendations designed to reduce overall portfolio default rates while maintaining loan growth targets.

---

## Business Problem
The lending division observed an uptick in 90+ day loan delinquencies over recent quarters, impacting net interest margin and increasing capital reserve requirements. 

**Core Objectives:**
* Identify demographic and financial indicators strongly correlated with loan default.
* Define risk-adjusted credit thresholds for loan approvals.
* Quantify potential financial savings from strategy adjustments.

---

## Key Business Insights

* Debt-to-Income (DTI) Ratio as a Primary Indicator:** Borrowers with a DTI above 40% exhibited a **3.2x higher default rate** compared to those below 25%.
* Credit Utilization Impact:** High revolving credit utilization (>70%) combined with short credit history (<3 years) accounted for 42% of total default losses.
* Income Verification Gap:** Unverified income applicants defaulted at 18.5%, compared to 7.2% for verified applicants in similar credit score bands.

---

## Strategic Recommendations & Business Impact

| Recommendation | Target Segment | Expected Business Impact |
| :--- | :--- | :--- |
| **Tighten DTI Caps** | Applicants with DTI > 42% | Reduces default exposure by an estimated $850k/year |
| **Mandate Income Verification** | Loans exceeding $15,000 | Lowers unverified default rates by ~40% |
| **Tiered Interest Pricing** | Revolving utilization > 60% | Offsets risk with a 1.5% APR risk premium |

---

## Data & Methodology

* **Dataset Size:** 50,000 historical loan records.
* **Metrics Analyzed:** Default Rate (DR), Expected Loss (EL), Loss Given Default (LGD), Debt-to-Income (DTI), FICO Score distributions.
* **Data Quality & Governance:** Cleaned missing values, checked for skewness, validated against business rule logic, and ensured full anonymization of PII (Personally Identifiable Information).
