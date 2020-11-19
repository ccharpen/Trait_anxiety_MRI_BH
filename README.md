# Trait anxiety in MRI vs behavioral-only studies
Dataset and code for large-scale analysis of trait anxiety scores in MRI vs behavioral studies
Current manuscript is available here: https://psyarxiv.com/cqdne/

### Data
In the dataset (Anxiety_all_data_revision.csv), each row represents one individual, and the columns represent the following variables:
- Trait anxiety: trait anxiety scores from the STAI-T (higher scores mean higher trait anxiety)
- State anxiety: state anxiety scores from the STAI-S (higher scores mean higher state anxiety)
- Study context: fMRI studies vs behavioural studies
- Age at the time of participation in study (in years)
- Gender: M (male), F (female)
- Stressor: whether the study used a stress induction procedure (1) or not (0)
- Drug: whether the study used a drug administration procedure (1) or not (0)
- Site: study site where data was collected (anonymized)
- Screening: whether participants were screened (1) or not (0) for psychiatric disorders before participation in the study
- Screening type: none (no screening), phone (phone interview), or full (in person structured clinical interview)
- Sample type: whether the study recruited participants from community samples, convenience samples (undergraduate students), or both
- Study duration (in minutes)
- Pay rate (in USD per hour)
- Anxiety research: whether the study was considered part of research on anxiety (1) or not (0)
- Post-exclusion: whether data was provided for this dataset before (0) or after (1) participants were excluded (e.g. for motion in fMRI studies, or poor performance, etc)
- Preliminary data: whether data was included in the preliminary dataset for hypothesis generation (1) or in the final dataset (0)

### Code
The code (Trait_anxiety_project_rev_clean.Rmd) was run in RStudio Version 1.3.959 and can be used to reproduce the analysis and graphs from the manuscript.
In order to run the script the directory on l.29 needs to be replaced with the directory in which the data was saved. Comments are included throughout the script to detail the different analyses.

### License
This repository is licensed under the terms of the Creative Commons Attribution 4.0 International Public License (CC-BY-4.0).
See the license file or this link for more details: https://creativecommons.org/licenses/by/4.0/
