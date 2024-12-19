# SDTM-and-ADaM-Mapping-using-SAS

The aim is to conduct SDTM and ADaM mapping for the "HIV Rapid Testing and Counseling in Drug Abuse Treatment Programs in the U.S." study (NIDA CTN Protocol 0032, December 12, 2008 Version 8.0). Demographics, adverse effects, disposition/study completion, and laboratory test results domains from the study are being mapped with the aid of implementation guides, study protocol, and annotated CRF. The resulting mapped data will then be used to develop code for producing tables, listings, and graphs.

SDTM mapping is the process of converting raw clinical trial data into the Study Data Tabulation Model (SDTM). ADaM mapping, on the other hand, involves converting data from SDTM into the Analysis Data Model (ADaM), which is a standardized format used for analyzing clinical trial data.

#### Objective: 

The objective is to process and combine multiple CSV files containing clinical trial data to create final datasets suitable for analysis.

#### Data Import:

CSV files containing clinical trial data are imported into SAS datasets using PROC IMPORT.
Each CSV file corresponds to specific data, such as demographics (DEM), randomization (RAN), adverse events (AE), and study completion (COMP).
Data from each CSV file is imported into separate SAS datasets.

#### Data Processing:

Data from multiple sources is merged into one dataset named "dem_total".
Final datasets are created by merging various datasets and assigning values based on specific conditions.
Certain variables are processed to create additional attributes required for analysis.


#### Final Datasets Created:

#### DM (Demographic Data):

Contains demographic information of subjects in the clinical trial.
Includes attributes such as age, sex, race, ethnicity, etc.

#### ADSL (Adverse Events Analysis Dataset):

Combines adverse event data with demographic information.

#### AE (Adverse Events Dataset):

Contains processed adverse event data.


#### Conclusion:

The SAS program successfully imports, processes, and combines clinical trial data to create final datasets suitable for further analysis.
The final datasets provide comprehensive information necessary for analyzing demographics, adverse events, and other relevant aspects of the clinical trial.
