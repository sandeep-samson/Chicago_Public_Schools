# Chicago Public Schools

## Introduction
Using this Python Notebook we will:
1. Understand three Chicago Dataset
2. Load the three Dataset into three tables in a SQL database
3. Excute SQL queries to answer questions

## Understand the datasets
To complete the given problems in the notebook we will be using three datasets that are available on the city of Chicago's Data Portal:
1. [Socioeconomic Indicators in Chicagp](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2/about_data?utm_content=000026UJ&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDB0201ENSkillsNetwork20127838-2021-01-01&utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_term=10006555)
2. [Chicago Public Schools](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t/about_data?utm_content=000026UJ&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDB0201ENSkillsNetwork20127838-2021-01-01&utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_term=10006555)
3. [Chicago Crime Data](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data?utm_content=000026UJ&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDB0201ENSkillsNetwork20127838-2021-01-01&utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_term=10006555)

### 1. Socioeconomic Indicators in Chicago
The dataset contains a selection of six socioeconomic indicators of public health significance and a "hardship index", for each Chicago community area, for the years 2008-2012.

A detailed description of the dataset and the original dataset can be obtained from the Chicago Data Portal at:

https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2

### 2. Chicago Public Schools
This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year. This dataset is provided by the city of Chicago's Data Portal.

A detailed description of the dataset and the original dataset can be obtained fron the Chicago Data Portal at:

https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

### 3. Chicago Crime Data
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occured in the City of Chicago from 2001 to present, minus the most recent seven days.

A detailed description of the dataset and the original dataset can be obtained from the Chicago Data Portal at:

https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

## Store the datasets in database tables
To analyze the data using SQL, it first needs to be loaded into SQLite DB. We will create three tables in as under:
1. **CENSUS_DATA**
2. **CHICAGO_PUBLIC_SCHOOLS**
3. **CHICAGO_CRIME_DATA**
