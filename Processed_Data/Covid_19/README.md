# 2020 - 2023 Covid Pandemic Time Series Data

## Data Files
| File Name | Description |
| --- | ---|
| `Covid_World_Domain_Daily_CumCases.csv` | Time Series Data for World Covid-19 Country level and Domain level daily confirmed cumulative case number |
| `Covid_World_Domain_Daily_CumDeaths.csv` | Time Series Data for World Covid-19 Country level and Domain level daily confirmed cumulative death number |

## Data Columns
| Column Name | Description |
| --- | --- |
| `Microbe Family` | Family name for the microbe that caused the pandemic |
| `Microbe Genus` | Genus name for the microbe that caused the pandemic |
| `Microbe Species` | Species name for the microbe that caused the pandemic |
| `Region` | The WHO region name for the data point |
| `Country` | The Country name for the data point |
| `Domain` | The state or province name for the data point |
| `Sub-Domain` | The city name for the data point |
| `date` | Date for the data point |
| `type` | type of the data, could be one of the following `[Cases, Cumulative_Cases, Deaths, Cumulative_Deaths, Weighted_Ratio]` |
| `number` | type value |



## Data Property
**Data Start Date** \
(World) 2020-01-03 \
(United States) 2020-01-21\
**Data End Date** \
(World) 2023-10-25 \
(United States) 2023-03-23 \
**Frequency** \
Daily \
**Location Type** \
(World) Country \
(United States) State \
**Num. of Locations** \
(World) 237 \
(State) 56 \
**Length of Time Series** \
(World) 1,392 \  
(United States) 548 - 1,158

## Data Source
(World) https://covid19.who.int/data \
(World, Domain Level) https://github.com/CSSEGISandData/COVID-19 \
(United States, Domain Level) https://www.nytimes.com/interactive/2021/us/covid-cases.html
