# DS-4002-Project2: Decoding University Admission Trends

The goal of this project is to gather data from the US Department of Education (US DOE) to determine if university admission and applicant rates changed over the past twenty years and what external factors influenced these trends. To do this we will first harvest data from the US DOE's website, clean the data, and then using the ARIMA model, we hope to determine whether admission rate fluctuations exists across public institutions, as proven through the use of MAE and MSE hypothesis testing.

Software and Platforms: All of the code created in this project was run through the google colab platform for the ease of collaboration and sharing. Packages that are used in the file include pandas, numpy, seaborn, matplot, sklearn, and math functions. All of these package downloads are included in the code to make sure that anyone who runs the code can reproduce the results. The program was run across different computers but the online nature of the coding process prevented any problems with the type of computer platform that we individually used.

File Directory:

README.md : This document contains general information about the project and files included in this Repo

LICENSE.md : Licensing and copyright reproducibility information

DATA FOLDER This folder contains all data files, both raw and cleaned, that are used in the project.

Final_dataframe (1).csv : This dataframe is the final clean dataset that we used to conduct analysis.

SCRIPTS FOLDER This folder contains any code used in the project:

Project 2 Code.ipynb : This is the cleaning code that we used to reformat the raw data set downloaded from the US DOE website. This code also generates the visualizations that we used in our original data understanding phase. After consolidating the code, this also runs the analysis for our project.

OUTPUT FOLDER This folder contains any visual outputs used for preanalysis and understanding of the data set. Files in this folder are named according to their relevance.

Project 2 Presentation: This file includes the slides that will be presented in class.

Reproduction Instructions The first step for analysis replication is downloading the initial dataset indluded in the DATA folder above. Using this dataset, run the "Project 2 code.ipynb" to obtain the outputs and clean dataframe used in the analysis section. To return the results of the analysis, continue to run the code. This should produce identical results to the ones that we achieved.

