# An Ontology-based Approach for Harmonization and Cross-cohort Query of Alzheimer's Disease Data Resources
This repository contains the mapped and harmonized data elements between National Alzheimer's Coordinating Center (NACC) and the Alzheimer's Disease Neuroimaging Initiative (ADNI) as well as the Alzheimer's Disease Data Element Ontology (ADEO) modelling the mapped data comments.

- The AD_concepts folder contains the results of data element mapping and coding inconsistency harmonization between NACC and ADNI.
  - The concepts file stores the mapped data elements between NACC and ADNI which are also modelled as concepts in ADEO.
  - The variables file stores the original variable names and types for the mapped data elements in NACC and ADNI. 
  - The variables_concept_mapping file stores the correspondence between ADEO concepts and original variable names in NACC and ADNI.
  - The domain file contains the permissible values and corresponding value codes for categorical variables.
  - The inconsistency file contains the harmonized results of inconsistent values codes for categorical variables 
- The ADEO.owl is the source file of the Alzheimer's Disease Data Element Ontology. 
- The ADEO_OMOP_Mappings file contains the mappings between ADEO concepts and OMOP Standardized Vocabulary.
