# Project Details

This page provides additional context on the design decisions and trade-offs
behind each project in this portfolio.

---

## Customer Churn Prediction
- SQL-first feature engineering mirrors warehouse workflows
- Logistic regression used as an interpretable baseline
- XGBoost added to capture non-linear behavior
- Feature importance extracted to support retention decisions

---

## LLM-Powered Analytics Copilot
- Metric layer enforces consistent definitions
- Query validation prevents unsafe or hallucinated SQL
- LLM usage is intentionally constrained and explainable
- Focused on trust and governance, not chatbot demos

---

## Causal Impact Analytics
- Variance reduction techniques improve decision speed
- Causal methods used to estimate true treatment effect
- Outputs designed for executives, not statisticians
