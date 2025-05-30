# Urban and rural population projected to 2050 - Data package

This data package contains the data that powers the chart ["Urban and rural population projected to 2050"](https://ourworldindata.org/grapher/urban-and-rural-population-2050?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Population residing in urban areas
Total urban population of a country over time.
Last updated: January 17, 2024  
Date range: 10000 BCE – 2050 CE  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
United Nations, Department of Economic and Social Affairs, Population Division (2018); HYDE (2023) – with minor processing by Our World in Data

#### Full citation
United Nations, Department of Economic and Social Affairs, Population Division (2018); HYDE (2023) – with minor processing by Our World in Data. “Population residing in urban areas” [dataset]. United Nations, Department of Economic and Social Affairs, Population Division, “World Urbanization Prospects Dataset”; PBL Netherlands Environmental Assessment Agency, “History Database of the Global Environment 3.3” [original data].
Source: United Nations, Department of Economic and Social Affairs, Population Division (2018), HYDE (2023) – with minor processing by Our World In Data

### What you should know about this data
* The projection method for urban population in the World Urbanization Prospects involves a two-step process using an established extrapolation method based on urban-rural ratios. Initially, the average annual rate of change in the urban-rural ratio is calculated using data from the last two censuses, which informs the rate of change in urban and rural populations. This rate is then extrapolated, assuming a logistic path of urban proportion growth. Subsequently, a "world norm" is applied, estimated from empirical urban-rural growth differences in two groups of countries categorized by population size. This norm uses a regression equation to establish a hypothetical urban-rural growth difference for different levels of initial urban percentage.

The country-specific urban-rural growth difference is then converged with this hypothetical difference over 25 years, allowing the urbanization process of a country to align with a global urbanization pattern. This method ensures that urban-rural growth differences evolve towards a worldwide trend rather than remaining constant.

### Sources

#### United Nations, Department of Economic and Social Affairs, Population Division – World Urbanization Prospects Dataset
Retrieved on: 2024-01-17  
Retrieved from: https://population.un.org/wup/Download/  

#### PBL Netherlands Environmental Assessment Agency – History Database of the Global Environment
Retrieved on: 2024-01-02  
Retrieved from: https://doi.org/10.24416/UU01-AEZZIT  


## Population residing in rural areas
Total rural population of a country over time.
Last updated: January 17, 2024  
Date range: 10000 BCE – 2050 CE  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
United Nations, Department of Economic and Social Affairs, Population Division (2018); HYDE (2023) – with minor processing by Our World in Data

#### Full citation
United Nations, Department of Economic and Social Affairs, Population Division (2018); HYDE (2023) – with minor processing by Our World in Data. “Population residing in rural areas” [dataset]. United Nations, Department of Economic and Social Affairs, Population Division, “World Urbanization Prospects Dataset”; PBL Netherlands Environmental Assessment Agency, “History Database of the Global Environment 3.3” [original data].
Source: United Nations, Department of Economic and Social Affairs, Population Division (2018), HYDE (2023) – with minor processing by Our World In Data

### What you should know about this data
* The projection method for urban population in the World Urbanization Prospects involves a two-step process using an established extrapolation method based on urban-rural ratios. Initially, the average annual rate of change in the urban-rural ratio is calculated using data from the last two censuses, which informs the rate of change in urban and rural populations. This rate is then extrapolated, assuming a logistic path of urban proportion growth. Subsequently, a "world norm" is applied, estimated from empirical urban-rural growth differences in two groups of countries categorized by population size. This norm uses a regression equation to establish a hypothetical urban-rural growth difference for different levels of initial urban percentage.

The country-specific urban-rural growth difference is then converged with this hypothetical difference over 25 years, allowing the urbanization process of a country to align with a global urbanization pattern. This method ensures that urban-rural growth differences evolve towards a worldwide trend rather than remaining constant.

### Sources

#### United Nations, Department of Economic and Social Affairs, Population Division – World Urbanization Prospects Dataset
Retrieved on: 2024-01-17  
Retrieved from: https://population.un.org/wup/Download/  

#### PBL Netherlands Environmental Assessment Agency – History Database of the Global Environment
Retrieved on: 2024-01-02  
Retrieved from: https://doi.org/10.24416/UU01-AEZZIT  


    