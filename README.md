# Instructor Effectiveness Modeling

Predicting instructor effectiveness tiers (Low/Medium/High) from batch-level EdTech data.
Uses a real dataset of 2000 batch records across 120 instructors and 25 courses, with metrics
like completion rate, quiz scores, engagement, and feedback. The data is aggregated to the
instructor level, scored with a weighted formula, and classified using logistic regression
and random forest models.

Everything lives in `instructor_effectiveness.ipynb`. The dataset is `data.csv`.
