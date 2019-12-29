# Audit_Risk

## Data Set Information:
This dataset is taken from a research explained here.
The goal of the research is to help the auditors by building a classification model that can predict the fraudulent
firm on the basis the present and historical risk factors. The information about the sectors and the counts of firms
are listed respectively as Irrigation (114), Public Health (77), Buildings and Roads (82), Forest (70), Corporate
(47), Animal Husbandry (95), Communication (1), Electrical (4), Land (5), Science and Technology (3), Tourism
(1), Fisheries (41), Industries (37), Agriculture (200).

There are two csv files to present data. Please merge these two datasets into one dataframe. All the steps
should be done in Python. Please don't make any changes in csv files. Consider Audit_Risk as target
columns for regression tasks, and Risk as the target column for classification tasks.

# Attribute Information:
Many risk factors are examined from various areas like past records of audit office, audit-paras, environmental
conditions reports, firm reputation summary, on-going issues report, profit-value records, loss-value records,
follow-up reports etc. After in-depth interview with the auditors, important risk factors are evaluated and their
probability of existence is calculated from the present and past records.

# Relevant Papers:
Hooda, Nishtha, Seema Bawa, and Prashant Singh Rana. 'Fraudulent Firm Classification: A Case Study of an
External Audit.' Applied Artificial Intelligence 32.1 (2018): 48-64.

# Project description:

Please read the Data Set Information section to learn about this dataset.
Data description is also provided for the dataset.

Read data into Jupyter notebook, use pandas to import data into a data frame
Preprocess data: Explore data, check for missing data and apply data scaling. Justify the type of scaling
used.

Regression Task:
Apply all the regression models you've learned so far. If your model has a scaling parameter(s) use Grid
Search to find the best scaling parameter. Use plots and graphs to help you get a better glimpse of the
results.
Then use cross validation to find average training and testing score.

Your submission should have at least the following regression models: KNN regressor, linear regression,
Ridge, Lasso, polynomial regression, SVM both simple and with kernels.

Finally find the best regressor for this dataset and train your model on the entire dataset using the best
parameters and predict buzz for the test_set.

Classification task:
Decide aboute a good evaluation strategy and justify your choice.
Find best parameters for following classification models: KNN classifcation, Logistic Regression, Linear
Supprt Vector Machine, Kerenilzed Support Vector Machine, Decision Tree.
Which model gives the best results?
Deliverables:
Submit IPython notebook. Use markdown to provide an inline comments for this project.
Submit only one notebook. Before submitting, make sure everything runs as expected. To check that, restart
the kernel (in the menubar, select Kernel > Restart) and then run all cells (in the menubar, select Cell > Run
All).
Visualization encouraged.
