# San Francisco Crime Rate Analysis using Apache Spark

## Project Overview
This project utilizes Apache Spark to analyze over 1.5 million crime records from public datasets, providing insights into crime patterns across San Francisco. By leveraging Spark SQL, PySpark DataFrames, and custom geospatial filtering techniques, the project uncovers trends in crime types, high-risk areas, and time-based distributions.

## Key Features
- **Data ETL Pipeline**: Built a scalable ETL pipeline to load, clean, and transform crime data using PySpark DataFrames and SQL.
- **Geospatial Analysis**: Applied custom UDFs and filtering to analyze crime within specific geographic areas, such as downtown San Francisco.
- **Temporal Analysis**: Combined weekly and hourly crime data to identify peak crime times and assess the impact of policy changes on crime rates.
- **High-Risk Area Identification**: Found Southern, Mission, and Northern districts to be the highest-risk areas, with theft-related crimes peaking in the evening and nighttime hours.

## Insights and Recommendations
- **Public Safety**: Advised increased caution in high-risk areas and times, especially in the evening.
- **Law Enforcement**: Suggested focused patrols in Southern, Mission, and Northern districts during peak crime hours to address frequent offenses like theft.

### CONCLUSION

Using Spark SQL, I extracted and analyzed critical data from vast datasets, applying various calculations and visualizations to present the results more intuitively. The analysis of crime data in San Francisco revealed a general increase in crime rates before 2018, with a noticeable decrease afterward. Additionally, the SOUTHERN, MISSION, and NORTHERN districts exhibited the highest crime rates, with LARCENY/THEFT being the most frequent type of crime, and most crimes remaining unresolved. These findings suggest potential factors such as policy changes, population growth, and individual behaviors, leading to the following recommendations: individuals should be particularly cautious with their belongings during meal and entertainment times, while law enforcement should explore more effective methods to reduce crime rates.

This project demonstrates the value of big data analytics in enhancing public safety strategies and optimizing law enforcement resource allocation.
