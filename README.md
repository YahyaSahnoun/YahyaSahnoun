<div align="center">

# Yahya Sahnoun

### Data Engineering Student · ENSA Khouribga, Morocco

Building batch data pipelines and lakehouse-style platforms with Spark, Airflow and Docker.<br>
**Looking for a 6-month PFE internship in Data Engineering (2027).**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-YahyaSahnoun-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/YahyaSahnoun)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yahya-sahnoun)

</div>

---

## About me

I'm a third-year engineering student in Computer Engineering and Data Engineering (Génie Informatique et Ingénierie des Données) at ENSA Khouribga, and I also study at École 1337.

I like the part of data work that happens before the dashboard: ingesting, cleaning, orchestrating and serving data reliably. At **Banque Populaire** I did a Data Engineering internship building a Big Data eligibility-scoring pipeline over 21 source tables and 3.17 million clients, and at **CIH Bank** a Data Analytics internship on KPI dashboards. I'm now looking for my end-of-studies internship (PFE) in 2027.

---

## Technical skills

**Languages & querying**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white)

**Processing & lakehouse**<br>
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

**Orchestration & streaming**<br>
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Storage & ingestion**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Hadoop HDFS](https://img.shields.io/badge/Hadoop%20HDFS-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Apache Hive](https://img.shields.io/badge/Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black)
![Apache NiFi](https://img.shields.io/badge/NiFi-728E9B?style=flat-square&logo=apachenifi&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)

**Infrastructure & cloud**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure%20(fundamentals)-0078D4?style=flat-square&logoColor=white)

**BI & visualization**<br>
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logoColor=black)

---

## Featured projects

### 🏦 [Savings Eligibility Big Data Platform](https://github.com/YahyaSahnoun/big-data-project)
End-to-end data and ML platform that predicts savings-product eligibility for bank clients, fully containerized with Docker Compose. Apache NiFi ingests raw data into MinIO (S3-compatible data lake), PySpark jobs clean it and train/score a Spark MLlib model, Airflow orchestrates the pipeline through a DAG, and a Hive Metastore plus Spark Thrift Server expose the results to BI tools like Power BI.
<br>`PySpark` `Spark MLlib` `Airflow` `NiFi` `MinIO` `Hive Metastore` `Docker`

### ⚡ [Spark + MySQL Docker Lab](https://github.com/YahyaSahnoun/setup-spark-cluster)
A self-contained Docker Compose environment with a Spark 3.5 standalone cluster (master, worker, client) and MySQL 8, for practicing both PySpark and Scala, including DataFrame ↔ MySQL work over JDBC. Documented with an architecture diagram and a version-compatibility table.
<br>`Spark` `PySpark` `Scala` `MySQL` `Docker Compose`

### 🎬 [Movie Recommendation System](https://github.com/YahyaSahnoun/Recommendation-System)
Recommender on MovieLens 100k comparing classic collaborative filtering (KNN, SVD, NMF) with deep-learning approaches (Neural Collaborative Filtering, AutoRec), served through an interactive Streamlit app.
<br>`Python` `PyTorch` `scikit-learn` `Streamlit`

### 🩺 [Medical Document Summarization Benchmark](https://github.com/YahyaSahnoun/resumerMed) *(in progress)*
Engineering-year project benchmarking extractive, abstractive (BART) and LLM + RAG summarization on medical text, focused on factual faithfulness rather than ROUGE alone.
<br>`NLP` `RAG` `Ollama` `Python`

**Also built (not published as public repos yet):** an end-to-end Databricks pipeline with PySpark, Spark SQL, Delta Lake and dbt (Bronze/Silver/Gold layers with data-quality tests), and a containerized Hadoop HDFS cluster extended across several machines with Docker Swarm.

---

## Let's connect

I'm open to PFE opportunities in data engineering starting in 2027. The best way to reach me is through [LinkedIn](https://www.linkedin.com/in/yahya-sahnoun), and the rest of my code lives on [GitHub](https://github.com/YahyaSahnoun?tab=repositories).
