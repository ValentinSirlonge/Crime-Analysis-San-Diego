# Crime Analysis for San Diego
This project analyzes crime data for San Diego using SQL and Docker. The goal is to explore geographic and temporal crime patterns and provide insights for enhancing public safety strategies.

## Project Overview
- **Objective**: Analyze crime data in San Diego to identify trends and inform public safety strategies.
- **Data Source**: Official San Diego government crime database, including crime categories, geographic locations, dates, and police service areas.
- **Database Design**:
  - Structured into 7 main tables with primary and foreign keys to enable complex queries and ensure data integrity.
  - Includes details on crime types, locations, neighborhoods, and geocoding.

## Key Features
1. **Database Queries**:
   - **Category 1: Crime Location**:
     - Identifies neighborhoods and divisions with the highest crime rates.
     - Example query: Crimes by division and neighborhood.
   - **Category 2: Crime Types**:
     - Explores the frequency of violent and property crimes.
     - Example query: Total violent crimes by type.
   - **Category 3: Temporal Statistics**:
     - Analyzes crime trends by day, month, and year.
     - Example query: Crimes by month in 2023.
   - **Category 4: Crimes by Neighborhood**:
     - Details crimes by neighborhood and type.
     - Example query: Crimes by neighborhood and crime type.
   - **Category 5: Administrative Details**:
     - Focuses on legal code sections and administrative crime details.
     - Example query: Crimes by legal code section.
   - **Category 6: Geocoding and Division**:
     - Examines geocoding statuses and their distribution by division.
     - Example query: Crime count by geocode status.

2. **Database Management**:
   - Dockerized PostgreSQL database for portability and easy replication.
   - SQL scripts to clean, transform, and analyze the data.

3. **Visualization**:
   - Data-driven insights to prioritize law enforcement efforts in high-risk areas.
