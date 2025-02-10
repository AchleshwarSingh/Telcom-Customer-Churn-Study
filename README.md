# Telcom-Customer-Churn-Study

Business Problem Overview:

Telecom companies face high customer churn rates (15-25% annually). Retaining profitable customers is crucial due to high acquisition costs.

Objective: Predict churn for high-value customers in the Indian and Southeast Asian market using customer data from four months (June to September).

Churn Definition: Focused on usage-based churn where customers stop using services. High-value customers defined by top 20% revenue.

Data Preparation:

- Derive new features relevant to churn prediction.
- Filter high-value customers based on top recharge amounts.
- Tag churners based on zero usage in the fourth month.

Modeling Approach:

- Use PCA for dimensionality reduction due to large number of attributes.
- Build predictive models (e.g., logistic regression) to predict churn.
- Identify important predictor variables for churn using another model.
