# IST722 - dbt Cloud Data Pipeline Assignment

## Overview
This repository, `ist722dbt`, contains my work from the *Building Data Pipelines in dbt Cloud* assignment as part of my coursework at Syracuse University. Using dbt Cloud and Snowflake, I built and managed data pipelines, demonstrating skills in data transformation, ELT processes, and version control. The project is organized into subdirectories (`quickstart` and `demo`) to separate different pipeline activities.

## Skills Gained
- **Data Pipeline Development**: Created and managed data pipelines using dbt Cloud, transforming raw data into structured tables and views with SQL-based declarative coding.
- **ELT with Snowflake**: Integrated Snowflake as a cloud data warehouse, mastering the Extract, Load, Transform (ELT) workflow for efficient data processing.
- **SQL Proficiency**: Leveraged SQL to define data transformations, building on existing knowledge to create reusable and standardized models.
- **Version Control with Git**: Set up and connected a GitHub repository (`ist722dbt`) to dbt Cloud, committing changes and managing project subdirectories for collaboration and organization.
- **dbt Cloud Navigation**: Configured dbt Cloud accounts, set up Snowflake connections, and utilized the interface to initialize projects, manage environments, and generate data lineage documentation.
- **Team Collaboration Tools**: Explored Git integration features in dbt Cloud, preparing for collaborative data engineering workflows.
- **Problem-Solving**: Troubleshot errors (e.g., restarting the IDE) and adapted to project subdirectory structures to avoid merge conflicts.

## Repository Structure
- **quickstart/**: Contains the dbt project files for the Quickstart tutorial, including models and configurations.
- **demo/**: Houses an additional demo project to practice switching between dbt environments.

## Tools & Technologies
- **dbt Cloud**: Data transformation and pipeline orchestration.
- **Snowflake**: Cloud data warehouse for ELT processes.
- **GitHub**: Version control and repository management.
- **SQL**: Core language for defining transformations.

## Screenshots
- **dbt Cloud UI**: Displays the `models` folder contents from the `quickstart` project. 
- **Data Lineage**: Generated documentation showing the flow from sources to targets.
  
![dbt Cloud Models](https://github.com/gudashashank/ist722dbt/raw/main/cloud_models.jpg)

## How to Explore
1. Clone this repository: `git clone https://github.com/gudashashank/ist722dbt.git`
2. Open the `quickstart` or `demo` subdirectories to view dbt project files.
3. Check the commit history for a step-by-step progression of the setup and pipeline development.

## Reflections
This assignment deepened my understanding of modern data engineering practices, particularly how dbt simplifies pipeline creation while maintaining scalability and collaboration. Integrating Snowflake with dbt Cloud honed my ability to manage cloud-based data workflows efficiently.
