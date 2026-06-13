# TeamSync-Student-Team-Compatibility-Classifier-
Machine learning project that forms compatible student teams using behavioural survey data and clustering techniques.

# Student Team Compatibility Classifier (TeamSync)

## Overview

Student Team Compatibility Classifier (TeamSync) is a Machine Learning project designed to create compatible student teams based on behavioural characteristics rather than random assignment.

The system analyzes survey responses related to work habits, communication preferences, productivity patterns, leadership tendencies, and project goals. Using clustering and classification techniques, it identifies natural student groups and automatically assigns new students to the most suitable team.

---

## Problem Statement

Traditional team formation methods often ignore behavioural compatibility, resulting in communication issues, leadership conflicts, and uneven workloads.

This project addresses the problem by using Machine Learning to group students based on behavioural similarity, leading to more balanced and effective teams.

---

## Features

- Behavioral survey-based student profiling
- Synthetic dataset generation with realistic noise
- Data preprocessing and cleaning pipeline
- K-Means clustering for team discovery
- KNN classifier for new student assignment
- Decision Tree classifier for interpretable predictions
- PCA visualization of clusters
- Feature importance analysis
- Cross-validation and model evaluation
- Cluster heatmap visualization

---

## Dataset Features

The system models students using seven behavioural attributes:

| Feature | Description |
|----------|-------------|
| Late_Night_Pref | Early Bird vs Night Owl |
| In_Person_Pref | Remote vs In-Person Collaboration |
| Stress_Level | Stress Handling Capability |
| Target_Grade | Academic Ambition |
| Role_Pref | Leadership Preference |
| Skill_Diversity | Technical vs Documentation Skills |
| Pacing | Early Starter vs Procrastinator |

---

## Machine Learning Pipeline

Survey Data
↓
Data Cleaning
↓
Missing Value Handling
↓
Outlier Treatment
↓
Feature Scaling
↓
K-Means Clustering
↓
Cluster Label Assignment
↓
KNN & Decision Tree Training
↓
Model Evaluation
↓
Team Recommendation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Models Used

### Unsupervised Learning
- K-Means Clustering

### Supervised Learning
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

### Dimensionality Reduction
- Principal Component Analysis (PCA)

---

## Evaluation Metrics

- Elbow Method
- Accuracy Score
- Confusion Matrix
- Cross Validation
- Feature Importance Analysis
- PCA Visualization

---

## Results

- Successfully identified 5 behavioural student groups
- Achieved over 98% classification accuracy
- Generated interpretable behavioural clusters
- Enabled automatic team assignment for new students
- Identified key factors affecting team compatibility

---

## Future Improvements

- Real-world student survey integration
- Web application deployment
- Advanced clustering algorithms (GMM, DBSCAN)
- Personality assessment integration
- Real-time team recommendation system

---

## Authors

- Deepak Kumar Meena


## License

This project is developed for academic and educational purposes.
