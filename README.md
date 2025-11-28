# Unsupervised Learning for Mental Health Segmentation in Technology Workforces

**Context:** This project was developed as a Case Study for IU International University of Applied Sciences.

## Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Results](#results)

## Project Overview
This project analyzes the OSMI 2016 survey data to group tech employees into 4 distinct segments using K-Means clustering and PCA (Hybrid Scaling). 
The goal is to provide actionable HR decision support for mental health interventions in the technology sector.

## Repository Structure
```bash
├── mental-heath-in-tech-2016_20161114.csv       # Original raw dataset from OSMI 2016
├── mental_health_dataset_EDA.ipynb              # Exploratory Data Analysis and Clustering
├── mental_health_dataset_completely_cleaned.csv # Processed and cleaned dataset
└── mental_health_dataset_preprocessing.ipynb    # Data cleaning and preprocessing steps
```

## Prerequisites
The following Python libraries are required to run the analysis:
*   pandas
*   numpy
*   sklearn (scikit-learn)
*   seaborn
*   matplotlib

## How to Run
1.  Clone the repository.
2.  Install the required dependencies.
3.  Run `mental_health_dataset_preprocessing.ipynb` to clean the raw data and generate the cleaned CSV.
4.  Run `mental_health_dataset_EDA.ipynb` to perform the exploratory analysis, dimensionality reduction (PCA), and clustering (K-Means).

## Results
The analysis identified four distinct workforce segments: **Cluster 0 (The Young, New Employees)**, **Cluster 1 (The Core Workforce)**, **Cluster 2 (Experienced Self-Employees)**, and **Cluster 3 (Newly Self-Employed)**, each with unique mental health support needs and work characteristics.
