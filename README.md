# Advancing Dementia Research with UK Cohort Data [HDRUK(Dementia-Trial-Accelerator)]
## Data harmonisation scripts and mapping documentation for dementia cohort studies (OMOP CDM).

### Abstract
Dementia is a progressive neurological condition characterized by cognitive decline, memory loss, and impaired daily functioning, affecting millions worldwide. During my time working with HDR UK’s Brain Health team, I contributed to the harmonisation and analysis of multiple UK dementia cohorts, including JDR, REACT, SHARE, and Generation Scotland, using the OMOP Common Data Model (CDM). Building on the research skills I developed during my MSc in Computer Science, where I applied deep learning and AI to medical imaging, I extended my expertise to health data research, integrating, standardizing, and analyzing complex cohort datasets.

My work involved accessing large-scale electronic health records (EHRs) across multiple UK cohorts which includes JDR, REACT, SHARE, and Generation Scotlan and applying machine learning techniques to identify patterns, insights, and demographics suitable for Dementia Trials Accelerator research. I assessed cohort structures, aligned terminologies, and recommended strategies for cross-cohort interoperability, supporting trial teams in finding and pre-screening participants and enabling more efficient recruitment for dementia studies. This project demonstrates my ability to apply AI and data science to real-world health challenges, contributing directly to advancing dementia research and enhancing clinical trial readiness in the UK.

### Introduction
The Dementia Trials Accelerator (DTA) aims to expand opportunities for people at risk of or diagnosed with early-stage dementia to participate in research. During my time working with HDR UK, I contributed by harmonising multiple UK dementia cohorts including JDR, REACT, SHARE, and Generation Scotland using the OMOP Common Data Model (CDM).

#### My work included:
Standardizing cohort data for consistent analysis across studies.
Mapping terminologies and cohort structures to improve interoperability.
Supporting trial teams in identifying eligible participants, pre-screening, and streamlining invitations across datasets.
Engaging with stakeholders through frequent in-person and online meetings to understand project needs, provide updates, and align on research priorities.

This experience allowed me to apply and advance my health data research skills, helping DTA efficiently connect trial teams with the right participants and accelerate dementia research in the UK.

### Observational Medical Outcomes Partnership (OMOP) Standardisation
As part of my work with HDR UK’s Brain Health team, I applied the OMOP Common Data Model (CDM), a standardized data structure designed to harmonise healthcare data from diverse sources, including EHRs, claims, and registries, into a common format for research and analysis, using standardized vocabularies such as SNOMED, ICD, and LOINC to define clinical concepts, for example, representing dementia with specific SNOMED codes.

### ETL Process in the Dementia Trials Accelerator (DTA)

The Dementia Trials Accelerator (DTA) enables clinical trial teams to efficiently identify and recruit participants by harmonizing data from multiple UK dementia cohorts. A key component of this initiative is a robust ETL (Extract, Transform, Load) pipeline that standardizes and integrates cohort data into the OMOP Common Data Model (CDM).

1. Extract:
Volunteer and trialist data are collected from various sources, including registries (JDR, SHARE, REACT, Generation Scotland), electronic health records (EHRs), and study-specific questionnaires. Data includes demographics, clinical assessments, cognitive measures, and consent for recontact.

2. Transform (My Contribution):
I mapped each dataset into the OMOP CDM, standardizing cohort structures (e.g., person, condition_occurrence, measurement) and aligning clinical and questionnaire data to standard vocabularies such as SNOMED, ICD, and LOINC. This involved resolving inconsistencies in terminology, formats, and time points, ensuring interoperability across cohorts while maintaining data quality.

3. Load:
The harmonized data is then loaded into the OMOP CDM database, making it accessible through HDR UK’s Discovery tools. This allows researchers and trial teams to perform cohort discovery, pre-screen participants, and facilitate recruitment efficiently, all within a secure and standardized environment.

By directly mapping datasets to OMOP standards, my work ensured that data from diverse cohorts could be analyzed and queried consistently, supporting real-world dementia research and enabling impactful clinical trial matching.
 
![Image](https://github.com/user-attachments/assets/8937a938-c53f-4e30-9324-f20ab231ada2)
  ### Data Collection and Pre-processing(ETL Life-Cycle)
  
![Image](https://github.com/user-attachments/assets/aa15697b-59e0-4e15-8208-d392be0f7df1)
  ### Comparative Analysis on the Various Cohorts

![Image](https://github.com/user-attachments/assets/38e8453e-eb21-4c7f-9681-684f3254da95)
  ### Generation Scotland's Data Analysis Visualisation

