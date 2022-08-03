# Data-Engineering-Change-and-Automation
After building an ELT data pipeline with PostgreSQL database for the data warehouse DBT for tansformation and redash for visualization, this project is about shifting to new tools for ELT.

Prerequisites

Make sure you have docker installed on local machine.

    Docker
    DockerCompose

Installation

    1. Clone the repo

    git clone https://github.com/Stella-Mutacho/Data-Engineering-Change-and-Automation 

    2. Datawarehouse

    cd sensor_data

    Run

     3. docker-compose up

      To access and Modify the default configrations for each tool use the .env files.

## MYSQL:

    Navigate to `http://localhost:8080/` on the browser
    use `mysqldb` server
    use `airflow` database
    use `airflow` for username
    use `airflow` for password

## Postgress:

    Navigate to `http://localhost:8080/` on the browser
    use `postgres-dbt` server
    use `dbtdb` database
    use `dbtuser` for username
    use `pssd` for password

## Airflow

Airflow is used for aurchestration and automation.

Navigate to `http://localhost:8080/` on the browser
use `airflow` for username
use `airflow` for password

DBT:

DBT performs the T in the ELT process, transforming the data in the warehouses.

    Airflow is used for automation of running and testing dbt models
    navigate to https://sensordataelt.herokuapp.com/index.html to access dbt docs

## Redash

open terminal and execute `docker-compose run — rm server create_db`
using adminer create a user and grant read access
Navigate to `http://localhost:5000/` on the browser

## Superset

    navigate to localhost:8088 to access Airflow

## Contribution

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

    Fork the Project
    Create your Branch (git checkout -b feature/NewFeature)
    Commit your Changes (git commit -m 'Add some NewFeature')
    Push to the Branch (git push origin feature/NewFeature)
    Open a Pull Request

