COVID-19 Vaccination Analysis and Visualization Using AWS QuickSight

Key Objectives
Data Collection: Accquire datasets from reliable sources
Data Processing: Clean and preprocess the data for analysis
Data Analysis: Identify different patterns in our data
Data Visualization: Develop interactive dashboards in AWS QuickSight

Data Source
Kaggle COVID-19 vaccination dataset

Data Storage
Amazon s3: Store raw data securely and processed data
Amazon RDS (PostgresSQL): Store structured data for efficient querying and analysis

Data Processing
AWS Glue: Perform ETL (Extract, Transform, Load) operations to clean and prepare the data for analysis

Data Visualization
Amazon QuickSight: Develop interactive dashboards

Security and Monitoring
AWS IAM: Authentication and Authorization ( Manage the identity and manage the access)
AWS Cloudwatch ( Monitoring service. Monitor our jobs, Monitor quicksight dashboards for performance and errors)

Solution Architecture
Workflow Overview
1. Data Ingestion
Download vaccination dataset from kaggle
Upload raw csv files to s3 in a secure bucket

2. ETL with AWS Glue
Create AWS Glue Crawlers to catalog dataset
Develop ETL jobs to clean, transform and load data into Amazon RDS

Example Transformations
Convert date fields to ISO format
Handle missing/null values

3. Data Storage
Structured and cleaned data in Amazon RDS for efficient querying

4. Visualization in QuickSight
Connect Amazon QuikSight to RDS or S3 (via Athena)
Build Interactive Dashboards and visualizations as
  Total vaccinations over time by country
  Vaccinations rate by population segment
  






