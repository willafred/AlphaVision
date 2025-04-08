# Mutual-Funds-Forecasting

The project aims to conduct a comparative analysis between machine learning models for forecasting the performance of mutual funds from the technology and healthcare sector. The dataset used was obtained from the CRSP database. 

## Directory Structure

The table below describes the folders and key datafiles used:
| Folder / File Name | Description |
| ---------  | ------------- |
| archived | Previous datafiles and code |
| raw_data | Stores raw fund level and macro factors involved in the generation of the datasets |
| scripts | Relevant scripts |
| df_ff_factors_healthcare.csv | Healthcare data used for analysis |
| df_ff_factors_tech.csv | Technology data used for analysis |
| healthcare_with_combi.csv | Overall healthcare results (including forecast combinations)
| tech_with_combi.csv | Overall technology results (including forecast combinations) |

Next, the table below describes the scripts used in the report.

| File Name | Description |
| ---------  | ------------- |
| alpha_plots.ipynb | Code to generate alpha plots |
| data_extraction_healthcare.ipynb | Data extraction script for Healthcare sector |
| data_extraction_tech.ipynb | Data extraction script for Technology sector |
| eda.ipynb | EDA Code |
| forecast_combi.ipynb | Code to generate forecast combinations |
| traning_code_alpha.ipynb | Code for Models and Hyperparameter Tuning|