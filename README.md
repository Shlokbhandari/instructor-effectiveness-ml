# Instructor Effectiveness Modeling

Predicting instructor effectiveness tiers (Low/Medium/High) from batch-level EdTech data.
Uses a real dataset of 2000 batch records across 120 instructors and 25 courses, with metrics
like completion rate, quiz scores, engagement, and feedback. The data is aggregated to the
instructor level with mean and std features, scored with a weighted formula, and classified
using logistic regression and random forest models.

How to run:
- Clone the repo: git clone https://github.com/Shlokbhandari/instructor-effectiveness-ml.git
- Install the required libraries (see below)
- Make sure data.csv is in the same folder as the notebook
- Open instructor_effectiveness.ipynb and run all cells top to bottom

Requirements:
pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter

Install with:
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Files:
- instructor_effectiveness.ipynb — main notebook with all analysis, modeling, and interpretation
- data.csv — the dataset (2000 batch-level records)

👨‍💻 Author<br>
Shlok Bhandari<br>
B.E. Artificial Intelligence & Data Science
