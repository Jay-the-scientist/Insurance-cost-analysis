# Insurance-cost-analysis

This project analyzes factors influencing insurance charges and builds regression models to predict costs.

# Dataset
The dataset contains information on insurance customers including demographic factors (age, gender etc.), health factors (bmi, smoking status) and policy details (region, number of children).

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

# Objectives
The objectives of this analysis are to:

- Understand which factors most affect insurance charges through EDA
- Develop single and multivariable linear regression models
- Apply Ridge regression to improve performance
- Transform features and refit models to capture nonlinearity
- Evaluate different models to identify best for prediction

# Libaries/Tools
- Pandas: For data loading, cleaning and manipulation
- NumPy: For numeric processing
- Matplotlib, Seaborn: For visualization
- Scikit-learn: For modeling algorithms like linear regression, Ridge, polynomial features
- Jupyter notebooks: For interactive analysis

# Methods
Jupyter notebooks are used for:

Data loading and cleaning
Exploratory data analysis with plots
Linear/Ridge regression modeling
Polynomial feature transformation
Model evaluation metrics like R2
