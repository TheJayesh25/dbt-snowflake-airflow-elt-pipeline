# dbt-snowflake-airflow-elt-pipeline

## Project Overview
This project is a hands-on refresher of modern ELT workflows using Snowflake, dbt and Apache Airflow.
The project uses the TPC-H dataset available in Snowflake to demonstrate how raw analytical data can be transformed through a dbt staging/intermediate/mart workflow and orchestrated through Airflow using Astronomer Cosmos.

While the initial implementation follows a guided build, the project was used to revisit and consolidate concepts including:
- dbt project structure and model dependencies
- source definitions and data tests
- staging/intermediate/mart layers
- incremental understanding of dimensional/analytical modeling
- dbt macros and Jinja
- Snowflake integration
- Airflow orchestration
- Cosmos-based dbt task generation
- Dockerized Airflow development
