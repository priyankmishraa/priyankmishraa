# Priyank Mishra

**Data & Cloud Solutions Architect**

*I design data platforms, then live with them in production.*

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

**Most AI programmes do not fail on the model. They fail on the data underneath it.**

13+ years across data engineering, cloud architecture and platform delivery. Most of my work is enterprise modernisation: moving companies off legacy ETL onto Snowflake, Databricks and AWS, and making the result something a team can actually operate.

---

### The diagram everyone draws

```mermaid
flowchart LR
  A[Sources] --> B[Ingest] --> C[Lakehouse] --> D[Model] --> E[BI / ML / GenAI]
```

### The diagram that decides whether it survives

```mermaid
flowchart LR
A[Sources] --> B[Ingest] --> C[Lakehouse] --> D[Model] --> E[BI / ML / GenAI]
Q[Data quality] -.-> C
L[Lineage and catalog] -.-> C
P[Access control and PII] -.-> C
O[Cost and observability] -.-> C
R[Failure recovery and on-call] -.-> C
```

Most of my work lives in the second picture.

---

### What I am building here

Small, real projects that test what new platform features actually do. Build a working pipeline, break it the way it breaks in production, then fix it.

The failure is the interesting part, not the feature.

### Stack

**Data** Snowflake · Databricks · Delta Lake · Unity Catalog · Iceberg · dbt · Airflow · PySpark · Kafka

**AWS** Glue · EMR · Lambda · Step Functions · Athena · Redshift · S3 · Lake Formation · SageMaker

**Platform** Terraform · GitHub Actions · Docker · Python · SQL · Scala

### Writing and video

I share production lessons on YouTube, LinkedIn and X. Mostly what happens after the architecture diagram becomes a system somebody has to support at 2 AM.

[YouTube](https://www.youtube.com/@priyankmishraa) · [LinkedIn](https://www.linkedin.com/in/priyankmishraa) · [X](https://x.com/priyankmishraa) · [priyankmishra.in](https://priyankmishra.in)

Reach me at me@priyankmishra.in
