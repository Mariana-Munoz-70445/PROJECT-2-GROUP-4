# MARIANA MUNOZ: Sp26_71552_Group 4 

# Kevin Behlke:
# Guy Mayer: 
# David Moreno:
# Nadia Nazeem: 

## Component 1: DATASET DESCRIPTIONS
###   We chose the City Police Departments dataset from the Snowflake Marketplace, provided by Snowflake Public Data Free, and is listed as the Urban Crime Timeseries dataset. We chose this dataset because it is easy to understand and relevant to real-world situations, while still being complex enough to support meaningful analysis. Compared to datasets like economic indicators or housing finance reports, crime data feels more straightforward and relevant to everyday life.
###   The dataset is structured as a single table and contains 11,876,843 rows, with each row representing a specific combination of date, location, and type of crime. It tracks crime across several major U.S. cities, including San Francisco, Chicago, Seattle, Los Angeles, Houston, and New York City. Each record includes the date, ZIP code, city, type of crime (such as theft, battery/assault, or deceptive practice), and the number of times that crime occurred. Because the dataset spans different locations and time periods, it allows for comparisons across both geography and time.
###   One thing that makes this dataset more interesting is that each city updates its data at a different rate. For example, San Francisco, Chicago, and Seattle update daily, Los Angeles updates weekly, Houston updates monthly, and New York City updates quarterly. This adds a layer of complexity when comparing trends across cities, since the data isn’t reported in the same way everywhere.

### Key columns in the dataset include: 
| Column Name   | Data Type | Description                                                         |
| ------------- | --------- | ------------------------------------------------------------------- |
| DATE          | DATE      | The date associated with the reported data                          |
| GEO_ID        | VARCHAR   | A unique identifier for a geographic area (such as a ZIP code)      |
| CITY          | VARCHAR   | The city where the crime occurred                                   |
| VARIABLE      | VARCHAR   | An internal identifier for the type of crime                        |
| VARIABLE_NAME | VARCHAR   | A human-readable name for the crime category (e.g., theft, assault) |
| VALUE         | NUMBER    | The number of reported incidents for that crime on that date        |

### While the dataset does not define a formal primary key, each record can be uniquely identified by the combination of DATE, GEO_ID, and VARIABLE, which together act as a composite key.
### Overall, this dataset can be useful in a few different ways. Police departments could use it to better understand crime patterns and make decisions about resource allocation, while individuals could use it to stay informed about safety in different areas and make more informed decisions about where they spend their time.



## QUESTIONS & JUSTIFICATIONS
### 1. Which types of crime are most common in different neighborhoods?
#### This question is relevant to both individuals and police departments. For example, people who are planning to travel to or move into a city would likely want to understand what types of crimes are most common in certain areas. Someone might feel more comfortable living in an area with higher non-violent crime rates, like theft, rather than areas with more frequent violent crimes such as assault or battery, depending on their personal situation.

#### From a policing perspective, this information is also important because different types of crime require different strategies. A city or neighborhood with higher theft rates may require a different patrol approach compared to one with higher rates of violent crime. Understanding these patterns can help departments better allocate resources and respond more effectively.

### 2. How does crime vary day by day, and are there consistent patterns across cities?
#### This question focuses on identifying trends over time and seeing whether similar patterns exist in different locations. For example, certain crimes like theft might be more common during weekdays, while violent crimes could increase on weekends.
#### These patterns are especially useful for police departments when planning patrol schedules and resource allocation. If specific trends are consistent, departments can adjust staffing and focus based on when certain crimes are more likely to occur. Overall, analyzing these day-to-day patterns can help improve how resources are used to prevent and respond to crime.

## DATA MANIPULATIONS

## ANALYSIS & RESULTS
### QUESTION 1 CHART(S): Which types of crime are most common in different neighborhoods?
#### INTERPRETATION:
### Question 2 CHART(S): How does crime vary day by day, and are there consistent patterns across cities?
#### INTERPRETATION:

## STREAMLIT APP 



##### AI USAGE:
