# Analyzing-Operational-Drivers-of-Team-Productivity-in-Garment-Manufacturing

This project analyzes operational drivers of team productivity in garment manufacturing using real-world production data from the UCI Machine Learning Repository. Through exploratory data analysis, feature engineering, PCA, and machine learning models—including Gradient Boosting—the study identifies key factors such as target-setting, idle workers, incentives, workload complexity, and department type that influence productivity. The findings provide actionable insights for optimizing staffing, workflow allocation, and incentive strategies in manufacturing operations.

Dataset
Productivity Prediction of Garment Employees

Source: UCI Machine Learning Repository - https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees

Each row = one production team's performance for a single day (team-day).
This includes operational metrics (overtime, idle time, workers), incentive data, and productivity outcomes.

Purpose and Audience
This project identifies the key operational factors that influence team productivity in garment manufacturing.

Primary audience:

Factory Operations Managers
HR & Productivity Analysts
Why it matters:
This analysis will provide insights to help optimize:

Overtime planning
Incentive strategy
Workflow allocation
Research Questions
How do overtime, idle time, incentives, and team size impact actual productivity?
Do department (sewing vs finishing) or day type (weekday vs weekend) influence productivity differences?
Can PCA/FA combine correlated operational variables into meaningful “efficiency” components?
Hypotheses
H₁: Overtime increases productivity, but with diminishing returns.
H₂: Idle time has a non-linear effect — too little or too much reduces productivity.
H₃: Incentives are positively associated with productivity (up to an effective limit).
H₄: Productivity varies across departments and day types.
H₅: PCA/FA components will reveal latent operational factors like workload intensity and efficiency.
