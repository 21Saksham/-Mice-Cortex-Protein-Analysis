# Mice Cortex Protein Analysis 
## Project Overview
This project analyzed protein expression levels in the cerebral cortex of mice to classify them based on genotype, behavior, and treatment. The aim was to identify key proteins and understand biological mechanisms related to learning and memory in the context of Down syndrome.

## Problem Statement
Classification: Classified mice into categories based on genotype, behavior, and treatment.
Protein Identification: Identified proteins that discriminated between these categories.
Biological Insight: Explored learning and memory mechanisms, particularly in Down syndrome.
## Steps Involved
### Data Preprocessing
Handling Missing Values: Addressed missing data using imputation techniques like mean/median or KNN.
Normalization/Scaling: Standardized protein expression levels with Min-Max scaling or Z-score normalization.
Encoding Categorical Variables: Converted categorical data to numerical format using one-hot or label encoding.
### Exploratory Data Analysis (EDA)
Summary Statistics: Computed mean, median, and standard deviation for each protein.
Visualizations: Created histograms, box plots, and scatter plots to analyze data distribution and relationships.
### Feature Selection
Correlation Analysis: Removed redundant features by examining correlations.
Mutual Information: Identified informative features for classification.
Model-Based Selection: Used feature importance from models to select key features.
### Model Training
Data Splitting: Divided data into training (80%) and testing (20%) sets.
Model Selection: Experimented with models like Random Forest, SVM, and Neural Networks.
Hyperparameter Tuning: Optimized models using Grid or Random Search.
## Model Evaluation
Metrics: Evaluated models with accuracy, precision, recall, and F1-score.
Confusion Matrix: Visualized performance to understand true/false positives and negatives.
### Results Interpretation
Key Proteins: Identified proteins crucial for classification.
Biological Context: Discussed how findings related to Down syndrome and learning mechanisms.
