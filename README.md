# Pandemic-Database

## Introduction
This repository collects meta data for recent large pandemics taken place around the world. The dataset contains frequently reported case number, reproduction rate, transmission pathways, mortality rate, hospitalization rate, latent period, incubation period, and average hospitalization length for the recorded pandemics. 

## Selected Meta Features
| Features | Explanation |
| --- | --- |
| Basic Reproduction rate (R0) | The expected number of cases directly generated by one case in a population where all individuals are susceptible to infection.
| Transmission pathways | Whether the pathogen is transmitted through objects, blood, air, vector, and droplets. 
| Mortality rate | The rate of death during the pandemic
| Hospitalization rate | The rate of an infected patient being hospitalized
| Latent period | Number of days between being infected and capable of transmitting pathogens. 
| Incubation period | Number of days between being infected and the appearance of the first symptom.
| Average hospitalization length | The average number of days the patient stays in the hospital.

## Time Series Case Data
| Pandemic | Virus Family | Virus Genus | Virus Species | Frequency | Start Time | End Time | Collected Area | Data Source |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| COVID-19 | Coronaviridae	| Betacoronavirus	| SARS-CoV-2 | Daily | January 2020 | May 2023 | World | https://beta.healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh / https://covid19.who.int/data  |
| Ebola | Filoviridae	| Ebolavirus	| Ebola Virus, Sudan Virus, Tai Forest Virus, Bundibugyo Virus | Weekly | March 2014 | April 2016 | Africa | https://www.cdc.gov/vhf/ebola/history/2014-2016-outbreak/case-counts.html |
| SARS | Coronaviridae	| Betacoronavirus	| SARS-CoV-1 | Daily | March 2003 | July 2003 | World | https://www.kaggle.com/datasets/imdevskp/sars-outbreak-2003-complete-dataset |
| Dengue Fever | Flaviviridae	| Flavivirus	| DENV | Weekly | May 1990 | July 2010 | South America | https://www.kaggle.com/datasets/arashnic/epidemy |
| Monkeypox | Poxviridae | Orthopoxvirus	| MPXV | Daily | May 2022 | July 2023 | World | https://ourworldindata.org/monkeypox |
| Zika Virus | Flaviviridae	| Flavivirus	| Zika Virus | Weekly | November 2015 | July 2016 | South/Central America, Caribbean | https://www3.paho.org/data/index.php/en/mnu-topics/zika-weekly-en/ |
| Influenza | Orthomyxovididae | Influenza A, B, and C Virus	| --- | Weekly | December 1997 | July 2023 | United States | https://gis.cdc.gov/grasp/fluview/fluportaldashboard.html |
