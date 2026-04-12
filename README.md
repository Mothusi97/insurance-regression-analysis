Insurance Charges Prediction - Linear Regression
Project Overview
This project builds a Linear Regression model to predict medical insurance charges based on demographic and lifestyle factors. The model helps insurance providers understand key cost drivers and develop risk based pricing strategies.
Dataset
•	Source: Kaggle Insurance Dataset (insurance.csv) 
•	Records: 1,338 individuals
•	Variables:
Variable	Type	Description
Age	Numerical	Age of beneficiary (18–64)
Sex	Categorical	male / female
Bmi	Numerical	Body Mass Index (15.96 – 53.13)
Children	Numerical	Number of dependents covered
Smoker	Categorical	yes / no
Region	Categorical	northeast, southeast, southwest, northwest
Charges	Numerical (target)	Individual medical insurance bill
Requirements
Install the required Python packages:
bash
pip instal pandas numpy matplotlib seaborn scikit-learn statsmodels
Project Structure
Google Colab Environment
│
├── LinearRegression_Insurance_Analysis.ipynb   # Main notebook (downloaded from Colab)
├── insurance.csv                               # Dataset (uploaded to Colab runtime)
├── archive (2).zip                             # Original zip file (uploaded)
├── report.pdf                                  # Project report (submitted separately)
└── README.md                                   # This file (local/optional)
How to Run
Google Colab 
1.	Open Google Colab
2.	Upload the notebookLinearRegression_Insurance_Analysis.ipynb 
3.	Upload the dataset zip file (archive (2). Zip when promoted 
4.	Run all cells (Runtime →Run all) 
Key Steps in the Notebook
1.	Data Loading & Inspection – check structure, missing values, summary stats
2.	Exploratory Data Analysis (EDA) – histograms, boxplots, scatter plots, correlation matrix
3.	Data Preprocessing – one hot encoding of categorical variables
4.	Train Test Split – 80% training, 20% testing
5.	Model Training – Linear Regression using scikit learn
6.	Evaluation – MAE, MSE, R², baseline comparison
7.	Interpretation – coefficient analysis, business insights
8.	Improvement – log transformation to reduce skewness
Results Summary
Metric	Value
MAE	$4,181
R²	0.784 (78.4% variance explained)
Baseline R²	0.000
Top predictors (coefficients):
•	smoker_yes: +$23,651
•	bmi: +$337 per unit
•	age:  +$257 per year
Output Files
After running the notebook, you will obtain:
•	Trained linear regression model (in memory)
•	Evaluation metrics printed in the notebook
•	Residual plots for diagnostic checking
Report
A detailed PDF report is included with this submission. It covers:
•	Dataset suitability and data quality
•	EDA findings with interpretations
•	Model training and evaluation
•	Business recommendations
•	Limitations and future improvements
Author
•	Name: Mothushi Thoka
•	Date: April 2026
License
This project is for educational purposes as part of a data analytics assignment.
Acknowledgements
•	Kaggle for the Insurance dataset
•	scikit learn, pandas, matplotlib, seaborn developers

<img width="468" height="648" alt="image" src="https://github.com/user-attachments/assets/ee8163f2-9ee1-433a-8200-ed179c955cbf" />

