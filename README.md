# Insurance-cost-analysis
This project analyzes factors influencing insurance charges and builds regression models to predict costs.

# Objectives 
Perform exploratory data analysis (EDA) on customer data from an insurance company to uncover trends related to demographics, charges, and coverage. The goals are to: 

- Understand which factors most affect insurance charges through EDA
- Develop single and multivariable linear regression models
- Apply Ridge regression to improve performance
- Transform features and refit models to capture nonlinearity
- Evaluate different models to identify best for prediction


# Dataset
Often referred to as the *Medical Cost Personal Dataset*, the dataset contains information on insurance customers including demographic factors (age, gender etc.), health factors (bmi, smoking status) and policy details (region, number of children).

The target variable is the annual insurance charges in USD. There are 7 predictor variables that may impact costs.

| Parameter |Description| Content type |
|---|----|---|
|age| Age in years| integer |
|gender| Male or Female|integer (1 or 2)|
| bmi | Body mass index | float |
|no_of_children| Number of children | integer|
|smoker| Whether smoker or not | integer (0 or 1)|
|region| Which US region - NW, NE, SW, SE | integer (1,2,3 or 4 respectively)| 
|charges| Annual Insurance charges in USD | float|

# Installation
You can install the required python libraries using:
```bash
pip install pandas numpy matplotlib sklearn
```

# Methodology
Jupyter notebooks are used for:

Data loading and cleaning
Exploratory data analysis with plots
Linear/Ridge regression modeling
Polynomial feature transformation
Model evaluation metrics like R2

# Results
- Smoking status is the most significant driver of insurance charges  
- Higher BMI values are associated with increased charges, especially among smokers  
- Charges tend to increase with age  

# Visualizations

