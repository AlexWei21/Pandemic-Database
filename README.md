# Pandemic-Database

## Introduction
This repository collects the time series and meta data for past large pandemics taken place around the world. The time series dataset contains frequently reported case numbers, death numbers, or  recovery data for different pandemics, and the meta-data table contains the reproduction rate, transmission pathways, mortality rate, hospitalization rate, latent period, incubation period, and average hospitalization length for the recorded pandemics. 

**Currently contains data**
Covid-19 (2020-2023) \
Ebola (2014-2016) \
SARS (2003) \
Dengue Fever (1990-2010) \
Monkeypox (2022-2023) \
Zika Virus (2015-2016) \
Influenza/Flu (2009-2023)

## Data Folders and Files
|Data Folder|Description|
|---|---|
|`Past_Pandemic_Time_Series_Data`| The data folder that contains the processed time series data for past pandemics | 
|`Raw_Data`| The raw data folder that contains the raw data for past pandemics |
|`Internal`| The internal folder that contains the processing files and intermediate data archive files during processing |
| `Past Pandemic MetaData.xlsx` | The Excel sheet that contains the meta-data of different Pandemics| 

## Selected Meta Features
| Features | Explanation |
| --- | --- |
| `Basic Reproduction rate (R0)` | The expected number of cases directly generated by one case in a population where all individuals are susceptible to infection.
| `Transmission pathways` | Whether the pathogen is transmitted through objects, blood, air, vector, and droplets. 
| `Mortality rate` | The rate of death during the pandemic
| `Hospitalization rate` | The rate of an infected patient being hospitalized
| `Latent period` | Number of days between being infected and capable of transmitting pathogens. 
| `Incubation period` | Number of days between being infected and the appearance of the first symptom.
| `Average hospitalization length` | The average number of days the patient stays in the hospital.

## Time Series Data
| Pandemic | Microbe Family | Microbe Genus | Microbe Species | Frequency | Data Start Time | Data End Time | Collected Area | Data Length | Data Type | Data Source |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| COVID-19 | Coronaviridae	| Betacoronavirus	| SARS-CoV-2 | Daily | 2020-01-03 | 2023-10-25 | World | 1,392 | Case, Death | https://beta.healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh / https://covid19.who.int/data / https://www.nytimes.com/interactive/2021/us/covid-cases.html |
| Ebola | Filoviridae	| Ebolavirus	| Ebola Virus, Sudan Virus, Tai Forest Virus, Bundibugyo Virus | Weekly | 2014-03-25 | 2016-04-13 | Africa | 266 | Case | https://www.cdc.gov/vhf/ebola/history/2014-2016-outbreak/case-counts.html |
| SARS | Coronaviridae	| Betacoronavirus	| SARS-CoV-1 | Daily (Except for Sunday) | 2003-03-17 | 2003-07-11 | World | 96 | Case, Recovered | https://www.who.int/csr/sars/country/en/ / https://github.com/imdevskp/sars-2003-outbreak-data-webscraping-code|
| Dengue Fever | Flaviviridae	| Flavivirus	| DENV | Weekly | 1990-05-06 | 2010-06-27 | Peru, Puerto Rico | 936 | Case | https://www.kaggle.com/datasets/arashnic/epidemy |
| Monkeypox | Poxviridae | Orthopoxvirus	| MPXV | Daily | May 2022 | July 2023 | World | 504 | Case, Death | https://ourworldindata.org/monkeypox |
| Zika Virus | Flaviviridae	| Flavivirus	| Zika Virus | Weekly | November 2015 | July 2016 | South/Central America, Caribbean | 84 | Case | https://www3.paho.org/data/index.php/en/mnu-topics/zika-weekly-en/ |
| Influenza | Orthomyxovididae | Influenza A, B, and C Virus	| --- | Weekly | 2009-01-05 | 2023-10-09 | World | 771 | ILI Case | https://gis.cdc.gov/grasp/fluview/fluportaldashboard.html \ https://ourworldindata.org/influenza#:~:text=pandemic%20in%20history-,Seasonal%20flu%20kills%20hundreds%20of%20thousands%20of%20people%20worldwide%20each,on%20average%20across%20the%20world. |
