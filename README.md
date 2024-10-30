# DS-4002-Project2: Decoding University Admission Trends

The goal of this project is to analyze data from the US Department of Education (US DOE) to determine if university admission rates, as well as tuition rates, have changed over the past 20 years in the North and South regions of the United States. After gathering data from the US DOE website, we performed data cleaning and preprocessing to prepare for analysis. We used both Seasonal Exponential Smoothing (ETS) and ARIMA models to analyze trends and fluctuations in admissions over time. The ADF test was conducted to assess data stationarity, and when the admissions data was found to be non-stationary, the ETS model was employed to better handle trends and seasonality. The ARIMA model was used on the tuition data. Additionally, we applied paired t-tests to compare admissions and tuition rates between the two regions. 

Software and Platforms: All code for this project was developed and executed in Google Colab, ensuring ease of collaboration and reproducibility. The project makes use of several key Python packages: pandas for data manipulation and cleaning, matplotlib for visualizations such as time series plots and ACF/PACF plots, and statsmodels for conducting the ADF test, generating ACF and PACF plots, and fitting both the ARIMA and Seasonal ETS models. Additionally, scipy is used to perform paired t-tests for comparing admissions and tuition rates between the North and South regions, while numpy is employed for numerical operations throughout the analysis. All of these package downloads are included in the code to make sure that anyone who runs the code can reproduce the results. The program was run across different computers but the online nature of the coding process prevented any problems with the type of computer platform that we individually used.

File Directory:

README.md : This document contains general information about the project and files included in this Repo

LICENSE.md : Licensing and copyright reproducibility information

DATA FOLDER This folder contains all data files, both raw and cleaned, that are used in the project.

These datasets were the final datasets that we used to conduct analysis:
north_average_admission_rate_by_year.csv
north_average_tuition_by_year.csv
south_average_admission_rate_by_year.csv
south_average_tuition_by_year.csv

SCRIPTS FOLDER This folder contains any code used in the project:

Project_2_Analysis.ipynb : This is the cleaning code that we used to reformat the raw data set downloaded from the US DOE website. This code also generates the visualizations that we used in our original data understanding phase. After consolidating the code, this also runs the analysis for our project.

OUTPUT FOLDER This folder contains any visual outputs used for preanalysis and understanding of the data set. Files in this folder are named according to their relevance.

Project 2 Presentation: This file includes the slides that will be presented in class.

Reproduction Instructions The first step for analysis replication is downloading the initial dataset included in the DATA folder above. Using this dataset, run the "Project_2_Analysis.ipynb" to obtain the outputs and clean data frame used in the analysis section. To return the results of the analysis, continue to run the code. This should produce identical results to the ones that we achieved.

