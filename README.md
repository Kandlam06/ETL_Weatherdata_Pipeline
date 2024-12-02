# Weather Data ETL Pipeline

## Overview
The Weather Data ETL Pipeline automates the daily process of extracting, transforming, and loading (ETL) weather data from the Open-Meteo API into a PostgreSQL database. This project simplifies data collection and structuring, enabling effective analysis and insights into London's climate.

## Technologies Used
- **Apache Airflow**: Manages and orchestrates the ETL process.
- **PostgreSQL**: Stores and manages structured weather data.
- **Docker**: Ensures consistent application deployment across environments.
- **Open-Meteo API**: Provides real-time weather data.
- **DBeaver**: Visualizes and manages data interactively.

## Key Features
1. **Automated Data Extraction**: Uses Airflow's HttpHook to fetch weather data daily from the Open-Meteo API.
2. **Data Transformation**: Processes raw JSON data into a structured format for PostgreSQL storage.
3. **Data Loading**: Uses Airflow's PostgresHook to load structured data into the PostgreSQL database.
4. **Interactive Visualization**: Integrates with DBeaver for easy data exploration and trend analysis.
5. **Seamless Deployment**: Docker ensures consistent operation across different setups.

## Project Workflow
1. **Extraction**: Automatically retrieves daily weather data from the Open-Meteo API.
2. **Transformation**: Converts raw JSON data into a structured format suitable for storage.
3. **Loading**: Efficiently loads the transformed data into a PostgreSQL database.
4. **Visualization**: Analyze weather trends and patterns using DBeaver.

## Getting Started

### Prerequisites
- Install **Docker** on your system.
- Install **Apache Airflow** for pipeline management.
- Install **DBeaver** for data visualization (optional).

### Steps to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. **Set Up Docker**: Ensure Docker is installed and running on your system.
3. **Configure Airflow**:
   - Create an Airflow connection for the Open-Meteo API.
   - Set up a PostgreSQL connection with the required credentials.
4. **Start the Pipeline**:
   - Launch your Airflow instance.
   - Trigger the `weather_etl_pipeline` DAG to start the ETL process.

## Conclusion

This **Weather Data ETL Pipeline** demonstrates expertise in building scalable, automated data pipelines using modern tools like Apache Airflow, PostgreSQL, and Docker. It highlights skills in API integration, data processing, and analytics, making it an excellent addition to any data portfolio.

## Acknowledgments

- Thanks to the Open-Meteo API developers for providing weather data.
- Inspired by the need for efficient data processing in the modern, data-driven landscape.
Copy code








