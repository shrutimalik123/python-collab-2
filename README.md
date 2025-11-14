Data-Science-Readiness-Portfolio: CVS Health Data Scientist Roadmap

This repository documents my daily, practical exercises designed to master the core technical skills required for a mid-to-senior level Data Scientist role, with a specific focus on the requirements outlined by the CVS Health Data Scientist job description (Python, SQL, ML/DL, MLOps, and Healthcare Data).

I commit to solving one targeted problem daily and pushing the results to this repository.

📅 Daily Project Index

Day

Project File

Skill Focus

Description

Day 1

data_profiler.py

Python, Pandas, Data Cleaning, Feature Engineering

Simulated raw patient data, handled missing values (mean imputation for Age, categorical fill for Diagnosis), and engineered the Mean Arterial Pressure (MAP) feature.

Day 2

advanced_sql_sim.py

Python, Pandas Window Functions (SQL Simulation), Complex Data Aggregation

Simulated a complex SQL query using Pandas' .groupby().rank() method to partition and rank high-risk patients (using MAP) for targeted clinical intervention.

Day 3

TBD

Machine Learning, Model Training, Scikit-learn



Day 4

TBD

MLOps Fundamentals, Experiment Tracking (MLFlow/TensorFlow)



Day 5

TBD

Cloud Deployment (AWS SageMaker/GCP Vertex AI) Simulation



🛠️ Requirements & Setup

All scripts are written in Python and primarily use standard data science libraries:

pandas

numpy

scikit-learn (starting Day 3)

To run any script:

python <filename>.py
