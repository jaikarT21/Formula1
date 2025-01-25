# Formula1
 a cloud-based data engineering solution to ingest, transform, analyze, and report Formula 1 data retrieved from the ERGAST API. Implemented a scalable data platform using the Lakehouse architecture to ensure efficient data management and governance.

# Key Responsibilities:
### Data Ingestion:
- Utilized Azure Data Factory (ADF) to extract data from the ERGAST API and store it in the Raw Layer of Azure Data Lake Gen2 in Delta format.
Automated data ingestion pipelines for seamless data flow.
### Data Transformation:
- Leveraged Azure Databricks (PySpark and SQL) for cleaning, transforming, and enriching data in the Ingested Layer.
Applied Lakehouse architecture principles using Delta Lake for versioning and efficient query performance.
Designed data transformation workflows to populate the Presentation Layer with analytics-ready data.
### Data Governance:
- Implemented Unity Catalog in Databricks for fine-grained access control and metadata management across all layers.
  
### Data Analysis and Reporting:
- Integrated Azure Data Lake's Presentation Layer  for creating dynamic dashboards and interactive reports.
Enabled near-real-time reporting and insights for Formula 1 analytics.

### Pipeline Orchestration:
- Used Azure Data Factory to orchestrate end-to-end data pipelines and monitor workflow execution.

# Key Achievements:
 - Built a robust pipeline with reduced data latency and improved processing efficiency using Delta Lake.
Delivered analytical dashboards enabling stakeholders to analyze historical and real-time Formula 1 data trends.
Ensured scalability and maintainability with modular pipeline architecture.

# Technologies Used:
- Data Storage & Processing: Azure Data Lake Gen2, Delta Lake, Azure Databricks (PySpark, SQL)
- Data Orchestration: Azure Data Factory
- Reporting: Power BI
- APIs: ERGAST API
- Data Governance: Unity Catalog

# > REPORTS OF DOMINANT DRIVERS FROM F1

<img width="771" alt="databricks_dominant_drivers" src="https://github.com/user-attachments/assets/6c3d873f-90d1-4a1b-aee4-31164a3c8508" />

<img width="782" alt="databricks_dominant_drivers_by_avg_points" src="https://github.com/user-attachments/assets/696371df-726c-465c-b5d7-0bb9e0857307" />


# > REPORTS OF DOMINANT CONSTRUCTORS FROM F1 

<img width="855" alt="databricks_dominant_team" src="https://github.com/user-attachments/assets/cc17261a-7fa8-484a-baaf-87222c4d584f" />

<img width="629" alt="databriks_dominant_team_by_total_points_races" src="https://github.com/user-attachments/assets/d6446d15-a2b9-4614-aa21-a08af09dafad" />








