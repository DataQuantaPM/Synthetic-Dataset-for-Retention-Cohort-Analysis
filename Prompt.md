# Synthetic SaaS Retention Dataset Prompt

## Purpose

This prompt is designed to generate a realistic synthetic SaaS event dataset for retention and cohort analysis.

The dataset can be used for analytics portfolio projects, SQL practice, dashboarding, and business case analysis.

The main goal is to create event-level data that behaves like a real SaaS product system, so learners can practice analyzing user retention, churn, acquisition quality, feature usage, and business impact.

---

## Who This Is For

This prompt is best for learners who already understand basic analytics concepts such as:

- Event-level data
- Cohort analysis
- Retention rate
- Churn analysis
- SQL aggregation
- User journey analysis
- Basic SaaS business logic

If you are completely new to data analytics, it is better to start with a simpler public dataset first before building a custom synthetic dataset.

---

## What This Prompt Generates

The prompt generates a raw SaaS event dataset for a retention and cohort analysis case study.

The dataset is designed to answer questions such as:

- How does user retention change by weekly signup cohort?
- Which cohort has the weakest retention?
- Which acquisition source brings the most retained users?
- Do paid users retain better than free users?
- Does early feature usage improve retention?
- Which user segment should be prioritized for retention improvement?

The dataset should be exported as:

```text
saas_retention_events_raw.csv
