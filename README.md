<h1>Project Overview</h1>

This project builds an end-to-end Big Data Analytics solution for Healthcare to handle large, distributed datasets generated across hospitals, patients, treatments, and medical departments. The goal is to efficiently ingest, process, store, and analyze healthcare data to produce meaningful clinical and operational insights.

Batch data ingestion is handled using Apache NiFi, while Apache Kafka enables real-time streaming of healthcare records. The collected data is processed using Apache Spark with RDDs, DataFrames, and Spark SQL to analyze patient trends, disease patterns, treatment outcomes, and hospital performance. Processed data is stored in a Hive Data Warehouse, optimized using partitioning and bucketing for faster queries.

Analytical queries generate reports such as patient admissions, disease frequency, recovery rates, and department-wise performance. Finally, insights are presented through dashboards and reports, enabling data-driven healthcare decisions.

Overall, the project demonstrates a scalable, real-time healthcare analytics platform that improves efficiency and supports informed medical and administrative decisions.

<h1>Technologies</h1>
Apache Kafka – Real-time data ingestion
Apache NiFi – Data flow and pipeline orchestration
Apache Spark – Distributed data processing
PySpark – Data cleaning and transformations
Spark SQL – Querying structured healthcare data
RDDs & DataFrames – Data analysis and aggregation
Apache Hive – Data warehousing and analytics
Power BI – Interactive data visualization

<h1>Project Team</h1>

Chaithanya Sri Chevula

Dooli Vyshnavi 

Grandhe Mounika 

Ithadi Sushmitha

Ramya Sai pusarla

<h1>Project Objective</h1>

The objective of this project is to build an end-to-end healthcare big data analytics platform that enables real-time and batch processing of large volumes of patient and hospital data to generate actionable insights. The system is designed to ingest, process, store, analyze, and visualize healthcare data using Kafka, NiFi, Spark, Hive, and Power BI, helping healthcare organizations make data-driven decisions.
Integrates data from multiple sources such as patient records, lab results, and hospital systems.

Enables real-time and batch data ingestion using NiFi and Kafka.

Stores and manages healthcare data efficiently in HDFS.

Performs advanced analytics using PySpark DataFrames and RDDs for insights such as patient trends, disease frequency, and treatment outcomes.

Creates interactive dashboards in Power BI to visualize key healthcare metrics.

<h1>Data Pipeline</h1>

Healthcare data is ingested using Kafka and NiFi.

Data is processed and transformed using PySpark.

RDDs and DataFrames are used for filtering, grouping, and analysis.

Spark SQL enables structured queries on large datasets.

Processed data is stored and analyzed in Apache Hive.

Insights are visualized through Power BI dashboards.

<h1>Key Analysis</h1>

**Patient Admission Trends**
Analyzed patient admissions over time across hospitals and departments to identify seasonal patterns, peak load periods, and resource utilization trends.

**Disease Distribution**
Studied the frequency and spread of diseases across regions, age groups, and hospitals to understand major health risks and treatment demands.

**Treatment and Recovery Patterns**
Evaluated treatment types, recovery rates, and length of hospital stay to measure the effectiveness of different medical procedures.

**Hospital and Department Performance**
Measured hospital and department efficiency based on patient volume, treatment outcomes, and recovery rates.

**Medicine Cost Analysis**
Analyzed the cost of medicines prescribed for different diseases and treatments to identify high-cost medications and spending patterns.

**Insured vs Uninsured Treatment Analysis**
Compared treatment expenses, patient outcomes, and service usage between insured and uninsured patients to understand financial impact and accessibility of healthcare.

<h1>Visualization</h1>
<h4>The dashboard reveals trends in healthcare treatments across age, disease, and geography.</h4>
<ul><li>Middle-aged and senior groups (40–70) receive the highest number of treatments.</li>
<li>Psoriasis treatments show a rising trend in recent years compared to Asthma.</li>
<li>California leads in total treatments, while high-cost treatments dominate overall expenditure.</li>
<li>Cancer and stroke affect the most households, highlighting priority areas for healthcare planning.</li></ul>

<h1>Outcome</h1>
This project shows how integrating Kafka, NiFi, Spark, Hive, and Power BI builds a scalable healthcare analytics system capable of handling large volumes of data. The pipeline converts raw healthcare data into structured, analyzable formats using PySpark, RDDs, DataFrames, and Spark SQL, and stores it efficiently in Hive. The final insights are visualized through Power BI dashboards, enabling real-time monitoring, trend analysis, and data-driven healthcare decisions.































