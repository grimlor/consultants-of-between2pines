Software Engineer with 15+ years of experience delivering scalable batch and streaming data systems and APIs, thriving in environments that value adaptability, learning, and connectedness across teams. Strong ability to self-direct and input solutions that meet both technical and business goals.
Accomplishments
At Cognitiv, I created and optimized a 60TiB Spark processing job to do a nightly load of our ScyllaDB backup of the identity graph to Iceberg and ClickHouse.
At Virtana:
 I specified and implemented several technologies, including Snowflake and Airflow, in a data processing solution for their Cloud Cost Management SaaS product, leveraging Timestream, Spark, and Neptune.
Platform owner for the Spark-based processing backend of a cloud cost management SaaS product at Virtana Corp.
At Lightbend, I architected systems using Akka Platform with customers that can maintain 99% uptime, cut operational costs by 40%, and process 4x more data than the previous system.
At Microsoft:
 I led development and migration to retire legacy CDN & publishing intermediary to publish creatives directly to new CDN infrastructure, saving $1.5M per year during my tenure at Microsoft.
Responsible for the segregation of public vs private Microsoft store assets, making the win of the Jedi Contract possible.
Core Competencies
Data Streaming & Processing
Azure Databricks | Apache Spark | Apache Kafka | Apache Flink | Apache Airflow
Data Storage Technologies
Snowflake | AWS Redshift Spectrum | Apache Iceberg | AWS Neptune | AWS RDS using PostgreSQL | AWS Timestream | ClickHouse | MSSQL | MySql | CosmosDB | ScyllaDB | Cassandra
Infrastructure
Kubernetes | GitLab CI/CD | JKCfg | Terraform/grunt | AWS | Azure | GCP | Github Actions | Jenkins | TFS | Github |Gitlab
Quality
Behavior Driven Development | Test Driven Development | IOC/DI | Jupiter/Junit | Pytest-bdd | Ginko/Gomega
Languages & Frameworks
Python | Java | Scala | C# | JavaScript | Golang | Akka Platform (actor pattern)

Professional Work Experience
Key Project Highlights
Between2Pines Consulting
Client: Microsoft (via Bluprint)
Building quality checks for use in data processing, as unit tests, integration tests, and canaries
Implementing alerting through Application Insights
Client: Trinity Life Sciences (via Pivotal)
Developed Databricks pipelines, normalizing data from a raw lake to their consumption lake leveraging Iceberg, and into Snowflake for querying and reporting
Worked with business to establish QC rules and notifications
Built Airflow DAGs for orchestrating Databricks, later pivoting to using the native Workflows in Databricks
Client: Apple (via Intelliswift)
Ops-focused: helping users use internal Spark platform for securely copying data to/from HDFS/S3, debugging user errors and usage gaps, investigating problems by digging into Cassandra and Spark logs
Added metrics for tracking remaining jobs queued for Spark processing
Cognitiv
ID Graph to Data Warehouse (2024-Q2)
Created Spark job to load 60TiB ScyllaDB backup of graph edges in denormalized format to data warehouse, Clickhouse
Updated the schema and Flink jobs of all related warehouse tables to include updated graph representation.
Virtana
Cloud Cost Management Data Platform (2022-Q3 – 2024-Q1)
Identified and established Apache Airflow as our workflow solution, including creating design patterns for ease of onboarding new users
Identified and demonstrated Snowflake as a more performant alternative to AWS Redshift Spectrum.
Implemented Spark connectors for Snowflake, AWS Timestream and AWS Neptune to support a unifying data layer
Demonstrated the business and development value of BDD testing using Cucumber and pytest-bdd
Implemented AWS Lambda functions written in Go for batch processing of data into the streaming pipeline
Lightbend
Senior Consultant / Senior Solutions Architect (2021-Q1 – 2022-Q2)
Worked with sales reps to educate customers and assist in selling our commercial software and consulting
Architected systems with customers that can maintain 99% uptime, cut operational costs by 40%, and process 4x more data than the previous system
Evangelized new technologies via Meetups, Webinars, and Conference talks
Deals landed included:
Strategic partnership with Hexaware, an IT sourcing company
Freedom Financial, building services using Scala and Akka Platform
Sketchers, cloud-first transformation using Akka Platform in AWS
Intuit, InfoSec lunch-and-learn for Akka Platform and the Actor pattern
Apptio
Multibox Team (2019-Q2 – 2021-Q1)
Designed and implemented the collection of multi-tenant services to replace the Version Control feature in the Flagship product. This included: 
a read-only API
a streaming pub/sub system for writes using Kafka
multiple workers pulling from the stream topics and partitions
a stream splitter for getting messages back to the initiating tenants
an orchestrator to scale workers based on stream processing needs
Microsoft
Universal Store Fulfillment & Licensing (2018-Q2 – 2019-Q2)
Designed and implemented authorization mechanisms in fulfillment services to sandbox first- and third-party store offerings enabling private clouds. This was key to enabling gov-cloud support for the Jedi Contract
Designed and implemented a mechanism linking next-generation fulfillment service documents to legacy service documents



Campaign Publishing Manager (2015-Q2 – 2017-Q4)
Led development and migration to retire legacy CDN & publishing intermediary to publish creatives directly to new CDN infrastructure, saving roughly $1.5M per year
Implemented services and workflow for packaging creatives and publishing to downstream systems
Implemented tag management services in coordination with downstream systems
Google
P&G Rakuten Re-Architecture (2013-Q4)
Re-architected existing processes to better scale data ingestion processes and implemented them using technology compatible with the Google stack with a Python library 
Created as a generic mapper of CSV-to-CSV or XML-to-CSV with support for retrieving the data from an API specified in the configuration
