## Overview

This project focuses on building a comprehensive data engineering solution for an eCommerce platform utilizing Microsoft Azure services. The goal is to analyze user behavior and seller performance across various dimensions, enabling data-driven decision-making.

### Key Datasets

1. **Users Dataset**: The primary table capturing user information and activity on the platform.
2. **Buyers Repartition by Country**: An analysis of buyer distribution, segmented by country to understand regional market trends.
3. **Comparison of Sellers by Gender and Country**: A comparative analysis of seller performance based on gender and country, providing insights into demographic influences on sales.
4. **Countries with Top Sellers**: A dataset highlighting countries with the highest-performing sellers, helping identify key markets and opportunities for growth.

This project employs a range of Azure services, including Azure Data Factory, Databricks, and Azure Key Vault, to facilitate data ingestion, processing, and governance.
## Project Details

### Project Type

  - **Domains:** ECommerce
  - **Duration:** 3 weeks
  - **Azure Subscription:** Pay as You Go
  - **Resources Used:** ADF, ADLS GEN2, Databricks, Logic Apps, Key Vault, Repo, DevOps, CI/CD

### Data Processing

- **Type:** 
  - Batch Data Processing

### Data Sources

- **MySQL, SFTP

### Datasets Format

- **CSV, Parquet

### ADF Pipelines

- **6 Pipelines


### Cluster Configuration

  - Interactive single node cluster
  - Policy: Unrestricted
  - Access Mode: No isolation shared

### Authentication

- **System Assigned Managed Identity, Service Principal, or Access Token

### Performance Optimization Techniques

- Parallel Processing in ADF
- Data Compression Techniques
- Parameterization for Pipelines
- Utilizing Databricks Notebooks (Spark)
- Implementing Data Partitioning
- Incremental Data Loading

## Project Responsibilities

- Creating and managing metadata tables
- Setting up linked services and datasets
- Implementing ADF pipelines and triggers
- Utilizing Azure Logic Apps for email alerts
- Employing Azure Key Vault for secrets management
- Developing data transformation logic using Databricks notebooks
- Storing data in various layers (bronze, silver, gold) using ADLS GEN2
- Implementing data governance with Azure Active Directory and RBAC

## Challenges Faced

- Managing small files and duplicate records
- Resolving data mismatch and pipeline run timing issues
- Addressing Spark memory management challenges
- Optimizing standard vs. partitioned tables