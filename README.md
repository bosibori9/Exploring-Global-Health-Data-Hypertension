# Exploring Global Health Data: Hypertension Analysis

## Project Overview
This project analyzes global health data focusing on hypertension causal factors. Using Jupyter notebook, I explore datasets to uncover insights about 
hypertension prevalence, risk factors, and geographic distribution of these factors together with the effect of social-economic factors on the same.

**Objective:** There are two main objectives, first is to be able to explore the relationship between lifestyle factors and the prevalence of hypertension 
and the second is to able to be able to analyse the probability of dying based on health behaviours and treatments.

## Dataset
The analysis uses  dataset  from the WHO site. It encompasses comprehensive information regarding Obesity and Hypertension and other different
factors spanning from the year 1975 through 2021.

**Dataset Details:** The initial data set before any transformation consits of:

Number of Samples: 110316 records.
Number of Features: 6 attributes.

## Analysis Approach
- Data cleaning and preprocessing
- Exploratory data analysis of hypertension statistics
- Visualization of trends and causation
- Statistical analysis of correlations between hypertension and other health factors

## Key Findings
-Hypertension increases with the increase in level of the income groups.
-There seem to be a correlation between Hypertension and alcohol consumption, smoking, overweight 
-from the model: 
    Low income has large positive main effect (β = 10.586)
    Income moderates the effects of other variables
    Male effect varies by income level
    Alcohol and smoking effects differ across income groups


## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas for data manipulation
- Matplotlib/Seaborn for visualization
- Statsmodel and Sklearn for statistical analysis

## How to Run
1. Clone this repository
2. Open the Jupyter notebook `11582309_IIDS69061.ipynb`
3. Run the cells sequentially to reproduce the analysis/results.
   

## Future Work
Different method on handling the missing data by multiple imputation to see whether model performance will improve
Better comparison between the two models. 

## Author
Anita Bosibori
