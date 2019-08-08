# Exploratory analysis for MIMIC III

MIMIC III is an openly available electronic health record(EHR) data for ~60,000 patients. It has been collected from 2 sources - CareVue and MetaVision. 

## Repository Contents:

* metadata_ids : This folder contains the IDs corresponding to the various requiremenst to extract the information for the subjects
* data_analysis.ipynb : This notebook contains the basic analysis for the MIMIC III dataset
* AKI_data_extraction.ipynb : This notebook contains the code for extracting the relevant metadata corresponding to each subject and saving each requirement as a separate chunk CSV file.
* AKI_data_preparation.ipynb : This notebook is to combine the various chunks of data and aggregate on the basis of their timestamp.
* acute_airway_obstruction.ipynb : This notebook does the data extraction and preparation realted to acute airway obstruction and treatment
