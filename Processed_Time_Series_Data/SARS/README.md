# 2003 SARS Pandemic Time Series Data

## Data Files
| File Name | Description |
| --- | ---|
| `SARS_World_Country_Daily_Cases.csv` | Time Series Data for SARS country level daily confirmed case number |
| `SARS_World_Country_Daily_CumCases.csv` | Time Series Data for SARS country level daily cumulative confirmed case number |
| `SARS_World_Country_Daily_Recovered.csv` | Time Series Data for SARS country level daily recovery number |

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
2003-03-17 \
**Data End Date** \
2003-07-11 \
**Frequency** \
Daily (Except for Sunday) \
**Location Type** \
Country \
**Num. of Locations** \
37 \
**Length of Time Series** \
5 - 96 (Depends on Country)

## Data Source
https://www.who.int/csr/sars/country/en/ \
https://github.com/imdevskp/sars-2003-outbreak-data-webscraping-code
