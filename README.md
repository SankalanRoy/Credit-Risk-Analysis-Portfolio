# Credit-Risk-Analysis-Portfolio# Credit Risk & Portfolio Default Analysis

## Executive Summary
The objective of this analysis was to understand which customer, credit and loan characteristics are associated with higher observed default risk and where risk appears to be concentrated within the loan portfolio.

Using 1,457 loans, I established an overall portfolio default rate of 32.94% as the baseline and compared individual segments against this benchmark.

The analysis indicates that borrower credit quality is the strongest theme emerging from the portfolio. Customers with weaker credit profiles, particularly those with Poor FICO scores (300–579) and weaker Credit Grades such as Grade E, show higher observed default rates relative to the portfolio baseline. This suggests that the borrower's underlying credit profile provides a more meaningful risk signal than many basic loan characteristics.

Customer characteristics provide additional context. Housing status and employment length show differences in observed default behaviour and may help further segment borrowers, although these variables appear less informative than the core credit-quality measures.

In contrast, several loan characteristics do not show similarly elevated default rates. Loan amount, loan purpose, age and DTI display some variation between groups but do not demonstrate a consistent pattern of elevated risk relative to the portfolio baseline. Interest rate also shows variation, but the highest-risk category is based on too few observations to be considered a reliable primary risk indicator.

The repayment analysis adds a behavioural dimension to the findings. By identifying loans that eventually defaulted and comparing their repayment patterns with non-defaulted loans, the analysis can assess whether increasing late-payment behaviour provides an early indication of deterioration in loan performance.

Overall, the analysis suggests that credit quality should be the primary area of focus when assessing portfolio risk, with customer characteristics and repayment behaviour providing additional layers of segmentation and monitoring.

The next logical step would be to combine these factors through cross-variable analysis to determine whether specific combinations — such as Poor FICO + weaker Credit Grade — identify concentrated risk segments beyond what individual variables reveal.

This analysis identifies associations rather than causal relationships or individual-level predictions. The findings should therefore be used to support risk segmentation and lending decisions rather than to conclude that any single characteristic causes default.
---

## Business Problem
Lending institutions face a constant challenge when issuing loans: approving customers who are unable to repay can lead to increased defaults and financial losses, while rejecting customers who are capable of repaying can result in lost revenue and potential customers.

The business therefore needs to understand which customer, credit and loan characteristics are associated with higher observed default risk and where risk is concentrated within the loan portfolio.

Without a clear understanding of these risk patterns, lending decisions may rely on broad assumptions rather than evidence from historical loan performance.

**Core Objectives:**

The objective of this analysis is to identify and understand the characteristics and customer segments associated with elevated loan default risk by analysing historical customer, credit, loan and repayment data.

The analysis will:

Establish the overall portfolio default rate as a baseline.
Identify customer, credit and loan characteristics associated with higher or lower observed default rates.
Compare individual segments against the portfolio baseline to identify elevated-risk groups.
Analyse combinations of risk characteristics to determine whether specific customer profiles have more concentrated default risk.
Examine repayment behaviour to understand patterns associated with loans that eventually default.
Translate these findings into actionable insights that can support risk segmentation, lending decisions and ongoing portfolio monitoring, while balancing credit risk with business opportunities.

---

## Key Business Insights

Following the analysis of the loan portfolio, several key insights have emerged regarding where default risk is concentrated and which characteristics appear most relevant to portfolio performance.

Credit quality is the strongest observed indicator of default risk

The analysis shows that borrower credit quality is the clearest area of elevated risk. Customers with Credit Grade E and those with Poor Credit Scores (300–579) demonstrate default rates above the overall portfolio baseline of 32.94%.

This indicates that existing credit quality should remain a key consideration when assessing borrower risk. From a business perspective, greater attention should be given to customers with weaker credit profiles, particularly when these characteristics appear alongside other risk indicators.

Customer characteristics provide additional risk segmentation

Housing status and employment length also show differences in observed default behaviour. In particular, customers across the major housing categories — Mortgage, Own and Rent — contribute materially to the observed defaults, while customers with 0–9 years of employment demonstrate higher observed default rates.

These characteristics should not be considered standalone reasons for restricting lending. Instead, they provide useful additional context that can be combined with stronger credit indicators to create more meaningful risk segments.

Some loan characteristics provide limited evidence of elevated risk

The analysis does not show similarly elevated default rates across characteristics such as loan amount, loan purpose, age and DTI.

While these variables show differences between segments, they do not demonstrate a consistent pattern of risk above the portfolio baseline. This suggests that the business should be cautious about using these characteristics independently when assessing credit risk.

Interest rate requires further investigation rather than immediate action

The analysis identified a high default rate within the highest interest-rate category. However, this segment contains too few observations to provide sufficient evidence for it to be considered a primary risk indicator.

I would therefore recommend treating interest rate as an exploratory factor rather than making a lending decision based on this finding alone. Further analysis, particularly alongside Credit Grade and FICO Score, would help determine whether the relationship remains significant across larger segments.

Repayment behaviour provides an opportunity for ongoing risk monitoring

The repayment analysis provides an additional perspective beyond the characteristics available at loan origination. By comparing the repayment behaviour of loans that eventually defaulted with those that did not, we can identify whether increasing late-payment behaviour is associated with deterioration in loan performance.

**Overall Business Finding**

Overall, the analysis suggests that borrower credit quality is the primary area where elevated observed default risk is concentrated, with customer characteristics and repayment behaviour providing additional layers of insight.

The findings also indicate that not every variable should be treated equally. Rather than applying broad risk assumptions across the portfolio, the business could focus its attention on combinations of characteristics that identify specific, concentrated risk profiles.

The next stage of the analysis will therefore focus on cross-variable analysis to determine whether combinations such as Poor FICO + Credit Grade E, or weaker credit quality combined with housing or employment characteristics, produce materially higher default rates than the individual factors considered separately.

**These findings represent observed associations within the historical portfolio and should be used to support risk segmentation, lending decisions and portfolio monitoring, rather than interpreted as evidence that any individual characteristic directly causes default.**
---

## Data & Methodology

The analysis involved data cleaning and validation, joining multiple relational tables, exploratory data analysis, pivot-table and cross-tabulation analysis, default-rate and baseline comparison, risk segmentation, repayment behaviour analysis, and finally cross-variable analysis to identify concentrated high-risk customer profiles.
