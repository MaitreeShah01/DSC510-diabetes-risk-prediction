# DSC510-diabetes-risk-prediction

# Predicting County-Level Diabetes Risk Using Social Determinants of Health

**Course:** DSC 510 — Health Data Science | DePaul University | Winter 2026  
**Authors:** Maitree Shah & Sania Malik | Group 16  
**Framework:** CDC HI-5 (Health Impact in 5 Years)

## Project Overview
This project applies machine learning to predict which U.S. counties are at 
highest risk for Type 2 Diabetes using Social Determinants of Health (SDOH) data.
Using 2023 data across 2,879 U.S. counties, we compare Logistic Regression and 
Random Forest classifiers to identify high-risk counties and propose 
data-driven public health interventions.

## Key Results
- **Best Model:** Random Forest | AUC 0.829 | Accuracy 80.7%
- **Top Predictors:** Premature Death Rate (31%), Children in Poverty (22%), % Rural (16%)
- **High-Risk Counties Identified:** 753 out of 2,879

## Files
| File | Description |
|---|---|
| `health_ds_final_project.py` | Full analysis notebook (EDA, modeling, results) |
| `DSC510_Group16_Report.docx` | Written project report (8-10 pages) |
| `Powerpoint_Slides_Final.pptx` | Pecha Kucha presentation (20 slides, 20 sec each) |

## Tech Stack
Python, Scikit-learn, Pandas, Matplotlib, Seaborn, CDC Diabetes Atlas, County Health Rankings
