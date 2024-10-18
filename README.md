# AI-550 Group 8 : Antan & Vinay

## Introduction:

This repository explores the Adult dataset from the UCI Machine Learning Repository Becker, B. & Kohavi, R. (1996). Adult [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20. The cited Adult dataset from the UCI Machine Learning Repository presents a great dataset to be worked upon. This dataset provides a valuable resource for exploring the relationship between demographic, socioeconomic factors, and income level. It can be used to develop predictive models, conduct social science research, and gain insights into income inequality. The dataset contains census data used to predict whether an individual's annual income exceeds $50,000. 

## Data Handling :

### Data Source: The Adult dataset is downloaded from the UCI Machine Learning Repository (link provided above).

### Loading and Cleaning: 
Jupyter notebooks in this repository (EDA.ipynb, modelling_data.ipynb) load the data using pandas, handle missing values (e.g., imputation or removal), and address potential outliers. Data cleaning steps will be documented within the notebooks.

### Feature Engineering: 
Feature engineering techniques (e.g., one-hot encoding for categorical features, scaling for numerical features) might be applied to prepare the data for analysis and modeling. Details will be found within the notebooks.


## Exploratory Data Analysis (EDA)

### Jupyter Notebook: EDA.ipynb provides a comprehensive visualization and analysis of the dataset.

#### Univariate Analysis: 
This section explores the distribution of each feature using descriptive statistics (mean, median, standard deviation, frequency tables for categorical features) and visualizations (histograms, boxplots, etc.).

#### Bivariate Analysis: 
EDA.ipynb examines relationships between features using techniques like scatterplots, correlation analysis, and chi-square tests for categorical features.


## Correlation Analysis

Pearson correlation coefficients will be calculated between numerical features in EDA.ipynb to gauge the strength and direction of linear relationships.
The correlation matrix will be visualized as a heatmap to identify potential multicollinearity among features.
Formula: Pearson correlation coefficient (r) is calculated as:
r = (Σ(xi - x̄)(yi - ȳ)) / √(Σ(xi - x̄)²) * √(Σ(yi - ȳ)²)
where:
xi and yi are individual data points for features x and y
x̄ and ȳ are the means of x and y
Inferential Statistics

Hypothesis testing (e.g., t-tests) might be conducted in EDA.ipynb to compare means of continuous features between groups (e.g., income level).
The choice of test statistic will depend on the specific research question and data characteristics. Detailed explanations will be provided within the notebook.

## Chi-Square Test for Categorical Analysis

Chi-square tests will be employed in EDA.ipynb to assess the independence between categorical features and the target variable (income).
The χ² (chi-square) statistic measures the deviation between observed and expected frequencies in a contingency table.
Formula: χ² = Σ [(O_i - E_i)² / E_i] where:
O_i is the observed frequency for cell i
E_i is the expected frequency for cell i
Machine Learning Modeling

Jupyter Notebook: modelling_data.ipynb implements various machine learning models to predict income based on the features.

## Model Selection: 
This section discusses the selection of suitable machine learning algorithms for this classification task (e.g., logistic regression, decision trees, random forests, etc.). Justification for chosen models will be provided.

### Model Training and Evaluation: 
Training data will be used to fit the models, while a separate hold-out or cross-validation scheme will be employed to evaluate model performance. Metrics used for evaluation (e.g., accuracy, precision, recall, F1-score, AUC-ROC) will be explicitly stated.
### Hyperparameter Tuning: 
Model hyperparameters might be tuned (e.g., using grid search or random search) to optimize model performance. The process will be documented in modelling_data.ipynb.


## Disclaimer

The results and interpretations presented in this repository are for study purposes only. They may not be generalizable to other populations or contexts.

## Contribution

This repository includes two Jupyter notebooks:

1. EDA.ipynb: Created by Vinay Mittal

2. modelling_data.ipynb: Created by Antan Tyagi


## Citation
Becker, B. & Kohavi, R. (1996). Adult [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20.
