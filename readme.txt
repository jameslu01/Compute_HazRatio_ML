This file contains the 'readme' instructions for the manuscript titled:
"Computing the Hazard Ratios associated with Explanatory Variables using Machine Learning Models of Survival Data"
Authors: Sameer Sundrani and James Lu,*
*Corresponding author. Email: lu.james@gene.com 

All required packages for both R and Python are updated to RStudio v. ‘1.3.959’ and Python v. 3.7. 
For a complete list of R packages used and Python libraries, see the top of each R and iPython Notebook. 
------------------------------------------------------------------------------------------------------------------------------

To run each of the XGBoost codes and obtain the figures presented in the manuscript body:

1) Download and save the 'XGB_Code_Data' folder. This should contain relevant Jupyter notebooks for each Breast Cancer, Colon      Cancer and Pan-cancer as well as all datasets needed for running these notebooks.

2) Run each notebook with the exception of hyperopt tuning and use the pre-tuned parameters as labeled in the notebook for training each XGBoost model. All figures will be saved to the current working directory.

------------------------------------------------------------------------------------------------------------------------------

For obtaining the datasets used in XGBoost and CoxPH results:

1) Download and save the 'R_Code_Data' folder. This should contain the relevant R notebook for dataset creation and CoxPH modeling as well as a copy of the original Pan-cancer supplementary table used in this methodology.

2) Run all R scripts and functions. All corresponding results, tables, and figures will be saved accordingly. 

------------------------------------------------------------------------------------------------------------------------------

For the simulated dataset analysis:  

1) Download and save the 'R_Python_Simulated_Data' folder. This should contain the relevant R and Jupyter notebooks as well as the simulated dataset used, 'xgb_SIMDATA.csv.' 

2) To replicate XGBoost / CoxPH comparisons Run only the Jupyter notebook using the same preset hyperparameters. All figures will be saved to the current working directory. 

3) To create your own simulated dataset and corresponding CoxPH output, run the R notebook in its entirety. All tables and results will be saved to respective subdirectories automatically.