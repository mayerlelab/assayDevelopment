# assayDevelopment

Mahajan UM, Oehrle B, Sirtl S, Alnatsha A, Goni E, Regel I, Beyer G, Vornhülz M, Vielhauer J, Chromik A, Bahra M, Klein F, Uhl W, Fahlbusch T, Distler M, Weitz J, Grützmann R, Pilarsky C, Weiss FU, Adam G, Neoptolemos JP, Kalthoff H, Rad R, Christiansen N, Bethan B, Kamlage B, Lerch MM, Mayerle J, Independent validation and assay standardization of improved metabolic biomarker signature to differentiate pancreatic ductal adenocarcinoma from chronic pancreatitis, Gastroenterology (2022), doi: https://doi.org/10.1053/j.gastro.2022.07.047

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
