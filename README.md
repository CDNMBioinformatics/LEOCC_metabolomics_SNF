# LEOCC cohort: metabolomics SNF project
## author: Yulu Chen
## including: meta data and R codes

### meta data: LEOCC_meta_data.xlsx
#### The metadata file comprises a total of 592 individuals, out of which 455 individuals have plasma samples collected prior to COVID-19, and 137 individuals have plasma samples collected after COVID-19. This file contains plasma sample collection age, gender, race, ethnicity, BMI, smoking status, COVID severity and ICU admission.

### map file: ID_map.xlsx
#### This map file map the ID to the metabolomics file

### R code
#### 1_metabolomics_QC.Rmd: conduct quality control and calculated the basic statistic summary of metabolomics data from Metabolon Inc.
#### 2_SNF_parameter_selection.Rmd: conduct the parameter selection for SNF
#### 3_SNF_preCOVID_metabolomics: conduct SNF for pre COVID metabolomics, including estimate the residuals of metabolites, SNF, leave-one-out cross validation, association with clinical phenotypes, regression analysis for clinical phenotypes
#### 4_Recapitulate_afterCOVID_metabolomics.Rmd: conduct recapitulate for during/after COVID metabolomics, including estimate the residuals of metabolites, recapitulate, association with clinical phenotypes, regression analysis for clinical phenotypes
