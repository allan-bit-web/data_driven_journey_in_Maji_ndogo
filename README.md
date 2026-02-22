# data_driven_journey_in_Maji_ndogo

## Project Overview

This project explores a large water services database to understand water sources, visit patterns, water quality, and pollution issues in Maji Ndogo. I used MySQL to query and analyze multiple tables, extract key insights, and identify areas that require attention. The goal is to practice real-world data exploration and support data-driven decision-making for improving access to safe water.

## Data Exploration

- Listed all tables using `SHOW TABLES`.

    | Table Name           | Description                          |
    |----------------------|--------------------------------------|
    | water_source          | Stores information about water sources |
    | visits                | Logs visits to water sources          |
    | water_quality          | Contains water quality assessments   |
    | well_pollution         | Stores pollution test results         |
    | location               | Geographic location data              |
    | global_water_access    | National and regional water access data |
    | employee               | Survey staff information              |
    | data_dictionary        | Metadata about the dataset            |

- Identified 8 tables including water_source, visits, water_quality, and well_pollution.
- Retrieved the first 5 records from each table using SELECT statements.
- Used DESCRIBE to understand column names and data types.
- Interpreted what each table represents (water sources, visits, quality, pollution, locations, etc.).

- Queried the `location`, `visits`, and `water_source` tables using SELECT and LIMIT to understand the dataset structure.
- Identified key columns such as location_id, source_id, and time_of_record.
- Observed that visits and water_source tables are linked using foreign keys.
- Used the data_dictionary table to understand column definitions and metadata.