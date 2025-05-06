
# Reddit ETL Data Pipeline

This project provides a scalable, cloud-native Extract, Transform, Load (ETL) solution to ingest and analyze Reddit data. It demonstrates how to build a complete data pipeline using open-source tools and AWS services.

## Project Overview

The pipeline extracts data from Reddit, transforms and catalogs it using AWS Glue, stores it in Amazon S3, and loads it into Amazon Redshift for analytics. Data can then be visualized using tools like Power BI, Tableau, Amazon QuickSight, or Looker Studio.

This project is ideal for learning how to:
- Orchestrate data workflows using Airflow and Celery
- Automate schema discovery and data transformation using AWS Glue
- Implement hybrid querying with Athena and Redshift
- Handle unstructured and semi-structured data efficiently in the cloud

## Architecture Diagram

![ETL Architecture](./path-to-your-image.png)

## Tech Stack

- **Orchestration:** Apache Airflow, Celery, PostgreSQL (metadata DB)
- **Cloud Services:** Amazon S3, AWS Glue, Amazon Athena, Amazon Redshift
- **Visualization:** Power BI, Tableau, Amazon QuickSight, Looker Studio
- **Infrastructure:** Docker

## Pipeline Breakdown

1. **Data Extraction**
   - Extract Reddit data using custom scripts or Reddit API.
   - Scheduled via Apache Airflow DAGs.
  
2. **Transformation & Storage**
   - Clean and transform data with AWS Glue jobs and crawlers.
   - Store raw and transformed data in separate S3 buckets.

3. **Query & Load**
   - Load transformed data into Amazon Redshift.
   - Enable ad-hoc querying with Amazon Athena.

4. **Visualization**
   - Connect data warehouse to BI tools for interactive dashboards and reporting.

## Getting Started

Clone the repository and follow the setup instructions:

```bash
git clone https://github.com/your-username/reddit-etl-pipeline.git
cd reddit-etl-pipeline
```

> *Docker, AWS credentials, and environment variables must be configured. Setup guide coming soon.*

## Sample Use Cases

- Reddit sentiment analysis  
- Trending topic analysis over time  
- Subreddit activity heatmaps  
- Comment volume monitoring  

## Contact

If you're interested in collaborating or hiring for data engineering work, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/shreyasgk/) or email me directly.

## Tags

`#ETL` `#DataEngineering` `#AWS` `#ApacheAirflow` `#Redshift` `#Glue` `#Athena` `#RedditAPI` `#BigData`
