# Machine Learning Analysis of Clinical and Approved Compounds
'ChEMBL_sm_analysis - ChEMBL small molecule analysis'

The goal of this project is to perform an exploratory analysis and build machine learning models on a dataset of small molecules that are in the drug discovery pipeline. The initial data was aquired from ChEMBL (https://www.ebi.ac.uk/chembl/). The dataset of molecular parameters was generated from the SMILES code of each molecule and consisted of chemical features such as molecular weight, number of hydrogen bond donors, and number of rotatable bonds. The first step was to perform an exploratory data analysis to gain insights into the dataset and identify any patterns or trends. This involved visualizing the distributions of the chemical features, examining correlations between features, and exploring relationships between the features and the target labels.
Next, several machine learning models were built to predict the activity of the molecules against the target. The final model was chosen to be a Random Forest Classifier. The performance of the model was evaluated using cross-validation and various metrics such as accuracy, precision, recall. The final accuracy score was at around 57.5%.

Overall, this project demonstrates how exploratory analysis and machine learning can be used to gain insights and make predictions about small molecules in the drug discovery pipeline. This model has potential as an examination tool for novel small molecule drugs as it provides information on the determining molecular parameters for successful drug approval.

Note: I am actively working on this project. If you have any comments or suggestions, do not hesitate to contact me. This includes inquiries on the written code and any suggestions for potential small molecule drug analyses.

Required python packages:
numpy
pandas
matplotlib
seaborn
rdkit
scipy
sklearn
