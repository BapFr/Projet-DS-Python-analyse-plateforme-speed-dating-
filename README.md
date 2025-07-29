# Speed Dating Platform Analysis

This project was conducted during the 2022–2023 academic year as part of the *Python for Data Scientists* course at ENSAE Paris (2nd year, MSc in Data Science & Economics).

## Project Description

This repository presents an analytical study of a speed dating dataset sourced from Kaggle. The aim was to explore how individuals make decisions during speed dating sessions and to assess whether the platform under study yields meaningful matches.

The project was both a technical and behavioral exploration: it combined statistical data analysis with sociological insight into human preferences. We chose this dataset because it is unconventional and offers a rich ground for exploration and hypothesis testing.

## Research Questions

- Does the speed dating platform produce effective and meaningful outcomes?
- What are the key factors influencing the final decision of participants?
- Are there systematic patterns in how people rate each other or decide to match?

## Repository Structure

### Final Notebook

- [`Notebook_Final.ipynb`](https://github.com/BapFr/Projet-DS-Python-analyse-plateforme-speed-dating-/blob/main/Notebook_Final.ipynb):  
  This is the main notebook that consolidates all data cleaning, analysis, visualizations, and conclusions.

### Graphical Notebooks

- Folder: `graphical notebooks/`  
  Contains individual notebooks dedicated to producing specific plots or graphs. These were modularized to keep the final notebook readable and well-organized.

### Data Files

- `speeddating.csv`:  
  Raw dataset downloaded from Kaggle:  
  [Speed Dating Dataset on Kaggle](https://www.kaggle.com/datasets/polarbearyap/speed-dating)

- `speeddating modified.csv`:  
  A cleaned and preprocessed version of the dataset created in `Notebook_Final.ipynb`.

- `speeddating personal.csv`:  
  A customized version of the dataset (filtered and adapted for specific analyses), also produced in the final notebook.

## Technologies Used

- Python 3.9+
- Jupyter Notebooks
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization
- `scikit-learn` for basic machine learning models and preprocessing

## Key Outcomes

- Identification of the most influential features in participants' decision-making.
- Visual analysis of participant behavior across gender, age, interests, and perceived attractiveness.
- Modeling of match outcomes using classification models with decent predictive power.

## Authors

This project was carried out by Arthur Sabre, Oscar Legoupil and Baptiste Ferrere, three ENSAE students, as part of the 2nd-year (2022-2023) coursework in data science.

---
