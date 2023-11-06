# 2020 - 2023 Covid Pandemic Time Series Data

## Data Files
| File Name | Description |
| --- | ---|
| `Covid_World_Daily_Cases.csv` | Time Series Data for World Covid-19 daily confirmed case number |
| `Covid_World_Daily_CumCases.csv` | Time Series Data for World Covid-19 daily cumulative confirmed case number |
| `Covid_world_Daily_Deaths.csv` | Time Series Data for World Covid-19 daily death number |
| `Covid_World_Daily_CumDeaths.csv` | Time Series Data for World Covid-19 daily cumulative death number |
| `Covid_US_Daily_Cases.csv` | Time Series Data for US Covid-19 daily confirmed case number |
| `Covid_US_Daily_CumCases.csv` | Time Series Data for US Covid-19 daily cumulative confirmed case number |
| `Covid_US_Daily_Deaths.csv` | Time Series Data for US Covid-19 daily death number |
| `Covid_US_Daily_CumDeaths.csv` | Time Series Data for US Covid-19 daily cumulative death number |

## Data Columns
| Column Name | Description |
| --- | --- |
| `Microbe Family` | Family name for the microbe that caused the pandemic |
| `Microbe Genus` | Genus name for the microbe that caused the pandemic |
| `Microbe Species` | Species name for the microbe that caused the pandemic |
| `Region` | The WHO region name for the data point |
| `Country` | The Country name for the data point |
| `State/City` | The state or city name for the data point |
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
(World) https://covid19.who.int/data
(United States, State-Level) https://www.nytimes.com/interactive/2021/us/covid-cases.html
