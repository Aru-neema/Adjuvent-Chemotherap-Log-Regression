# Adjuvent-Chemotherap-Log-Regression

After reading the documentation, the audience (beginners, students, aspirational data analyst) will know how to do the following tasks:

Understand how to use logistic regression 
Get to know how to use GridSearch CV

Project Background- The purpose of this project was to make a logictic regression based regession model to predict whether adjuvent chemotherapy will lead to recurrence or death of patient

Case Steps
Following steps are taken to solve this case

1.1 Read the data, to do the necessary initial steps, and exploratory data analysis (Univariate and Bi-variate analysis).

1.2 To grid Search CV to find the best combination of hyperparameters

1.3 Run the logistic model with the optimal hyperparameters

1.4 Evalute the model using R-sqaured and confusion matrix


Descriptive analysis
Univariate Analysis Bivariate Analysis Graph analysis

Expected Outcome:
To come up with a predictive model thay can help predict the impact of adjuvent chemotherapy

Data Understanding
The dataset has 15 columns and 1858 rows.

Data Dictionary:
• id: id
• study: 1 for all patients
• sex: 1=male
• age: in years
• obstruct: obstruction of colon by tumour
• perfor: perforation of colon
• adhere: adherence to nearby organs
• nodes: number of lymph nodes with detectable cancer
• time: days until event or censoring
• status: censoring status
• differ: differentiation of tumour (1=well, 2=moderate, 3=poor)
• extent: Extent of local spread (1=submucosa, 2=muscle, 3=serosa, 4=contiguous structures)
• surg: time from surgery to registration (0=short, 1=long)
• node4: more than 4 positive lymph nodes
• etype: event type: 1=recurrence,2=death

Data preparation
Code Used: Python

Python Version: 3.8.8

Packages: Pandas, Numpy, Matplotlib, Seaborn, Sklearn 
