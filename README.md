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

From the above distributions area frequency histogram, the number of participants across regions is as follows: Tayside – 10,896, Glasgow – 9,415, Perthshire – 2,488, Grampian – 1,196, and Ayrshire – 72. A pie chart depicting sex distribution shows that 58.8% of participants are female and 41.2% are male.

The age distribution of Generation Scotland participants, visualized as a frequency versus age chart, is slightly skewed at both ends, with ages ranging from 18 to 95 years. This indicates participation across both young and older age groups, with a median age of 55.

The ethnicity distribution reveals that the majority of participants are White (22,824), followed by Asian (113), while Black participants are the least represented (16). During stakeholder meetings, I emphasized the importance of engaging underrepresented ethnic groups, highlighting that even minority populations could provide valuable insights for DTA cohorts. My input was appreciated, and I supported it with references to my analysis of the Generation Scotland dataset using artificial intelligence.

  
### Summary of limitations for OMOP transformation and clinical trial utility
#### Structural Misalignment
Some cohorts store clinical data in non-relational or wide-format structures that do not directly map to OMOP CDM concepts.
Some cohorts store bespoke(Customized) questionnaire data that doesn't map to OMOP CDM concepts. 
Inconsistent coding across timepoints (e.g. changes to cohort questionnaires over time)

#### Lack of Temporal Data for self-reported data
Inadequate capture of event dates for clinical encounters, which hinders longitudinal analysis. (Single date from cohort entry)

#### Challenges during OMOP mapping
Missing variable documentation (e.g. not enough information to understand data or structure)
Mapping region at a very high-level (e.g 5 levels for Scotland)
Mapping multiple granular ICD10 codes to high-level phenotypes (e.g. Dementia)



