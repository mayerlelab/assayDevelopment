# assayDevelopment

Details of codes are as follows:
**00_Demographics**: It consist of data cleaning and demographics information. It used function of ImputeTransformScale for imputation and scaling of all metabolites.

**01_elasticNet_glmnet**: This code performs grid search, cutoff finding and model selection for i-Metabolic signature. This notebook is dependent on CutOff function,

**02_elasticNet_glmnet_LowCA**: This code performs grid search, cutoff finding and model selection for i-Metabolic signature in subset of patients without CA19.9. This notebook is dependent on CutOff function.

**03_elasticNet_glmnet_LowCA_nonclinical**: This code performs grid search, cutoff finding and model selection for i-Metabolic signature in subset of patients with CA19.9 <37U/mL. This notebook is dependent on CutOff function.

**04_h2o_autoML**: This code performs automatic machine learning for feature reduction and selection of m-metabolic signature. This notebook is dependent on runH2Omodels function.

**05_h2o_autoML_LowCA**: This code performs automatic machine learning for feature reduction and selection of m-metabolic signature in subset of patients without CA19.9. This notebook is dependent on runH2Omodels function.

**06_model_comparisons**: This code performs comparison between MxPancreasScore, i-Metabolic signature and m-Metabolic signature.

**07_assay_preanalytics**: This code performs all preanalytics steps.

**08_h2o_autoML_LowCA_nonclinical**: This code performs automatic machine learning for feature reduction and selection of m-metabolic signature in subset of patients with CA19.9 <37U/mL. This notebook is dependent on runH2Omodels function.
