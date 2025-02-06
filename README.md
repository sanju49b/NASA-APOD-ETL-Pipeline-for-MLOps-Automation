# NASA-APOD-ETL-Pipeline-for-MLOps-Automation


This project demonstrates an ETL (Extract, Transform, Load) pipeline using Airflow to automate the process of extracting data from the NASA APOD (Astronomy Picture of the Day) API, transforming it, and loading it into a PostgreSQL database. The pipeline is containerized using Docker, and AWS RDS is used for the PostgreSQL database. This solution is designed to be part of a full MLOps workflow, providing automated data ingestion and storage that could be used in further machine learning projects.

Tools and Technologies
Astronomer.io for Airflow orchestration
AWS RDS for PostgreSQL database
Docker for containerization
Airflow for managing ETL tasks
PostgreSQL for storing transformed data
Python for scripting ETL steps
NASA API for fetching astronomy images and data
Project Setup
Prerequisites
Install Docker on your machine.
Set up an AWS account and create an RDS PostgreSQL instance.
Create an account on Astronomer.io and set up a project for managing Airflow.
Ensure Python 3.7+ is installed along with pip.
