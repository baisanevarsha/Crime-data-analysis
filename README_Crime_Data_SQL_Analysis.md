# Crime Data Analysis & SQL Database Development

## Overview

This project uses SQL to explore crime data across Indian states and major cities. The work involved designing a database, organizing crime-related datasets into structured tables, and writing queries to answer analytical questions about crime patterns, population-adjusted crime rates, and police case outcomes.

## Objectives

- Build a structured database from the provided crime datasets.
- Compare crime statistics across states and cities.
- Identify regions with relatively high and low reported crime counts and rates.
- Examine trends in violent crime between 2020 and 2022.
- Compare cases registered under the Indian Penal Code (IPC) and Special and Local Laws (SLL).
- Investigate how population size affects interpretation of crime statistics.
- Explore relationships between crime statistics, case-investigation outcomes, and cases filed against police personnel.

## Tools & Techniques

- **SQL** — database creation, schema design, joins, filtering, aggregations, and analytical queries.
- **Relational database design** — structuring related state- and city-level datasets for analysis.
- **Exploratory data analysis** — comparing crime counts, rates, and trends across regions.

*Note: The specific database platform was not specified in the project notes. Add MySQL, PostgreSQL, or another platform only if applicable.*

## Data

The project used a provided crime dataset with state- and city-level information. The analysis referenced tables covering:

- State-wise IPC crimes
- State-wise SLL crimes
- State-wise violent crimes
- Crime statistics by offence and city
- Violent-crime trends across metropolitan cities
- Population and police case-status measures

The exact original data source and licensing details were not included in the available project notes.

## Workflow

1. **Database setup:** Created a database and organized the supplied data into schemas and tables.
2. **Data integration:** Connected related datasets using SQL joins and relevant identifiers.
3. **Query development:** Wrote SQL queries to answer the assigned analytical questions.
4. **Comparative analysis:** Compared crime counts and rates across states and cities.
5. **Trend analysis:** Examined changes in violent crime across metropolitan cities from 2020 to 2022.
6. **Interpretation:** Summarized query results and considered how population size and case outcomes affect comparisons.

## Key Questions & Findings

### 1. Which states and cities had relatively low reported crime figures?

The analysis identified Lakshadweep, Ladakh, and the Andaman and Nicobar Islands among the union territories with the lowest reported figures, and Sikkim, Mizoram, and Goa among the states identified as relatively safe in the project analysis. Coimbatore, Surat, and Kozhikode were identified as cities with comparatively low overall crime counts in the analysed data.

### 2. How did crime figures vary across metropolitan cities?

The city-level analysis compared overall crime counts for 2022 and identified Delhi as having the highest figure among the cities listed, followed by Mumbai and Bengaluru. Coimbatore, Surat, and Kozhikode were among the cities with the lowest figures in the comparison.

### 3. What were the trends in violent crime from 2020 to 2022?

The project compared average yearly changes in violent-crime figures across metropolitan cities. The analysis reported increases for several cities, including Delhi, Pune, and Mumbai, while Chennai and Lucknow showed decreasing trends in the calculations presented.

### 4. How did state-level and city-level crime figures relate?

The project compared selected cities with their corresponding states, including Delhi, Mumbai/Maharashtra, Bengaluru/Karnataka, Hyderabad/Telangana, Jaipur/Rajasthan, and Coimbatore/Tamil Nadu. The write-up described broad alignment in some comparisons while also noting exceptions.

### 5. How did IPC and SLL crime patterns compare?

The analysis examined the relationship between IPC and SLL figures across states. The project write-up reported a correlation of approximately **0.37** between IPC and SLL crime rates and approximately **0.58** between their charge-sheeting rates.

### 6. Why does population adjustment matter?

The project compared raw case counts with population-adjusted rates. For example, the analysis reported an IPC crime rate of **1,424.1 per lakh population for Delhi** and **171.6 for Uttar Pradesh** in 2022, illustrating how rankings can change when population is considered.

### 7. Were crime figures associated with police case outcomes or cases filed against police personnel?

The project explored relationships between crime rates, charge-sheeting, pendency, and cases registered against police personnel. Its correlation analysis reported values of **0.50** for violent crime and police cases, **0.27** for IPC and police cases, and **0.17** for SLL and police cases.

## Skills Demonstrated

- SQL database creation and schema design
- Data integration using joins
- Querying and filtering structured datasets
- Aggregation and comparative analysis
- Crime-rate and trend analysis
- Correlation analysis
- Translating query results into written findings

## Notes & Limitations

- Findings reflect the provided dataset and the calculations recorded for this academic exercise; they should not be interpreted as definitive measures of actual safety or policing effectiveness.
- Raw crime counts and population-adjusted crime rates are different measures and should not be treated as interchangeable.
- Correlation does not establish causation. The reported associations do not prove that crime levels cause changes in charge-sheeting, pendency, or cases filed against police personnel.
- Some city-level values in the project notes are labelled as crime counts despite being decimal values. The units and calculation method should be checked against the original tables before making direct comparisons.
- The original dataset source, full schema definitions, and SQL query files were not included in the notes used to draft this README.

## Suggested Repository Structure

```text
crime-data-sql-analysis/
├── README.md
├── sql/
│   ├── database_setup.sql
│   ├── schema_creation.sql
│   └── analysis_queries.sql
└── results/
    └── findings.md
```

Only include files and folders that you actually add to the repository.

## How to Use

1. Load the provided crime datasets into your SQL database.
2. Run the database and schema setup scripts, if included.
3. Execute the analysis queries.
4. Review the results and compare them with the findings documented in this README.

## Project Type

Academic SQL and database analysis project.
