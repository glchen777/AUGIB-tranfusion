# AUGIB-tranfusion
1. Project Overview
  This repository proposes a multi-task learning (MTL) model to predict the need for blood transfusion in patients with acute upper gastrointestinal bleeding (AUGIB), as well as to estimate the appropriate type and volume of transfusion. The proposed model demonstrates improved predictive performance over existing scoring systems and aims to support clinical decision-making in transfusion management.
2. File Structure
  （1）preprocessing.ipynb
  Data cleaning, feature engineering, and dataset splitting for AUGIB clinical data. Includes handling of missing values, categorical variable encoding, and normalization.
  （2）modeling.ipynb
  Implementation of transfusion prediction models . Contains hyperparameter tuning, training loops, and performance evaluation metrics (precision, specificity, F1-score and more).
  （3）external_validation.ipynb
  External validation of the best-performing model using independent cohorts. 
  （4）visualization.ipynb
  Generation of ROC curves, confusion matrices, and SHAP value plots to interpret model decisions and performance.
3. Usage
  Pipeline Execution
  Run notebooks sequentially:
  bash
    jupyter notebook preprocessing.ipynb  
    jupyter notebook modeling.ipynb  
    jupyter notebook external_validation.ipynb  
    jupyter notebook visualization.ipynb
   
Dependencies include Python 3.8+, pandas, scikit-learn, XGBoost, matplotlib, and SHAP.
