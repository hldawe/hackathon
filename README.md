## Data guide to the UST-Global Hackathon on the 6th October 2020

### Overview
This guide provides an overview of all the data sources within the Covid-19 dataset used for the hackathon. To be used in conjuction with the associated API guides and notebooks containing examples of data innovation with the dataset.

### List of datasets within the Covid-19 dataset
All the data that collectively form our Covid-19 dataset are listed below, with sources and where and how we have enriched this data.

#### 1. Covid-19 incidence related data

#### Daily incidence rates (Local Authority level)
Reporting daily on the number of [newly recorded Covid-19 cases](https://coronavirus.data.gov.uk/cases) by Local Authority. This data also reports the Local Authority population size, enabling the incidence rate (typically per 10,000 or per 100,000 people) of Covid-19 to be derived.

This data can be accessed via [this API](https://coronavirus.data.gov.uk/cases) and a notebook with analysis examples is [here.](https://coronavirus.data.gov.uk/cases)

#### Daily incidence rates (Middle Layer Super Output Area level)
Reporting daily on the number of [newly recorded Covid-19 cases](https://coronavirus.data.gov.uk/cases) at the 
Middle Layer Super Output Area (MSOA). This data also reports the MSOA population size, enabling the incidence rate (typically per 10,000 or per 100,000 people) of Covid-19 to be derived. The data is updated daily, with a new column added each week, the `latest_7_days` column contains the latest data most of the time, if the column is null then the latest data is contained within the latest `wk_XX` column. 

This data can be retrieved via [this API](https://c19downloads.azureedge.net/downloads/msoa_data/MSOAs_latest.csv) and can be used in conjuction with any other dataset reporting at MSOA level, including the geojson that is available in section 4 below.

#### Daily NHS 111 and 999 Covid-19 Triage rates (Local Authority level)
NHS Digital publishes the number of NHS 111 and 999 triages for Covid-19 daily. Reporting by age and gender at a Clinical Commissioning Group (CCG) level, we have attributed these figures at a Local Authority level to make them comparable with other incidence and demography data and also the business and economic metrics we outline in section 3 below.


<details open>
<summary><strong>Section 1 API details</strong></summary>
<br>
  
| API Title | Description | Location | Filesize |
|-----------|-------------|----------|----------|
|           |             |          |          |
|           |             |          |          |
|           |             |          |          |

</details>



#### 2. Population demography related data

#### 3. Industry and economy related data

#### 4. GIS data

#### 5. Other data

