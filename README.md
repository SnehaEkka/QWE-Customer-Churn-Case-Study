# QWE Customer Churn Case Study

A data-driven investigation into customer attrition at QWE Inc., blending rigorous exploratory analysis with practical predictive modeling to guide business action. Developed as an in-depth project for BA815: Competing with Analytics Course (Fall 2024), this repository demonstrates end-to-end analytics applied to an authentic churn scenario in SaaS.

## Case Summary

QWE Inc., a subscription-based technology company, faced mounting challenges with customer churn as its business matured. Leadership sought not just to tally departures, but to proactively predict which customers were most at risk—and why. Tasked with this mission, a data scientist dove into the firm’s trove of usage and engagement records, extracting signals from variables spanning customer tenure, support history, product adoption, and behavioral changes.

Careful not to overfit intuition, the analysis zeroed in on how customer lifecycle, happiness metrics (CHI score), and service request patterns work in concert to shape churn risk. With management eager for actionable results, the deliverable included a ranked list of customers most likely to churn, alongside tailored insights into the top drivers for each individual’s risk.

> *Details and customer data are adapted and anonymized to respect all confidentiality restrictions of the case material.*

## Project Motivation

Why do customers leave, and can we anticipate their decision before it’s too late? This project aims to illuminate the churn problem, surfacing key predictors from dozens of available metrics—turning raw behavioral footprints into strategic intervention plans that can elevate QWE’s retention and long-term value.

## Dataset Overview

- **Scope:** ~6,000 real-world customer subscriptions sampled at QWE Inc.  
- **Features:** Customer age (months), churn status, CHI score (current & delta), number and severity of support cases, product usage/activity logs, and recent engagement change variables (“delta" features).
- **Target:** Churn within the next two months (binary outcome).

## Technologies Used

- **Python:** pandas, numpy, scikit-learn, seaborn, matplotlib
- **Analysis Environment:** Jupyter, Colab (reproducible notebooks)

## Analytics Journey: From Exploration to Impact

1. **Exploratory Insights**  
   Began by visualizing churn rates across customer ages, service tenure, and recent engagement shifts. Found a notable spike in churn among accounts 6–14 months old—a cohort still forming habits but not yet deeply embedded in product value.
2. **Feature Engineering**  
   Incorporated both static and “delta” variables (recent shifts in CHI, support tickets, usage patterns) to better capture early warning signs of disenchantment.
3. **Predictive Modeling**  
   Built a logistic regression to predict churn risk, optimizing for interpretability so actionable drivers would be transparent to business users.
4. **Individualized Interventions**  
   For each of the top 100 at-risk customers, surfaced the three key features most responsible for their predicted churn likelihood, empowering targeted and cost-effective outreach.
5. **Visualization & Communication**  
   Delivered plots and dashboards highlighting risk distribution, driver importance, and actionable customer segments—making it easy for QWE’s retention team to move from insight to action.

## Selected Key Findings

- **Risk Stratification:** Churn concentrated in customers aged 6–14 months; both newcomers and very established users showed lower churn.
- **Actionable Drivers:** Drops in CHI score, increased recent support cases, and reduced product activity (logins/views) emerged repeatedly as leading signals.
- **Targeted List:** Generated a prioritized list of the 100 customers most likely to leave, with individualized breakdowns of their top risk contributors.

By combining predictive analytics with a business-centric communication of “why” and “what next,” the project enables QWE to proactively retain high-risk accounts, optimizing both cost-effectiveness and customer experience.

## Reflections

This case demonstrates the power of combining statistical rigor with clear, business-facing reporting. The approach—rooted in best practices for analytics consulting—connects data signals to practical decisions, illustrating a path from technical findings to measurable impact on retention.

To see the analyses, model outputs, and actionable customer rankings, explore the notebook and supplementary files provided.  
For feedback, discussion, or collaboration, please reach out via this repo.
