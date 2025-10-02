# Spark-Databricks-SQL-API-Streaming-Deep-Learning 

## (Individual project from my Big Data Analytics Master's 2020 batch)

A PySpark / Databricks combining **SQL queries, API integration, streaming pipelines, and deep learning inference**.  
This repository contains multiple scripts (developed as assignments during a Master’s program in Big Data Analytics) that demonstrate how to build scalable data workflows on Spark.

---

## Table of Contents

1. [About the Project](#Project-Overview).
2. [Prerequisites & Setup](#Prerequisites-&-Setup). 
3. [Usage](#Project-Usage). 
4. [Tutorial Walkthrough](#Assignment--Summaries). 

---

## Project Overview 

This repository demonstrates how Spark and Databricks can be leveraged to address real-world data engineering and machine learning challenges.  

The assignments demonstrate:
- Batch and streaming **data ingestion**  
- **Spark SQL** transformations and queries  
- Calling **external APIs** from Spark pipelines  
- Applying **deep learning models** for inference on streaming data  

It is designed as an educational project, but can also be a reference for developers starting with Spark + ML pipelines.

---

## Prerequisites & Setup

#### You’ll need the following installed:

- Python 3.7+  
- Apache Spark (or a Databricks environment)  
- Python libraries (install via pip):  

	```
 	pip install pyspark pandas numpy requests tensorflow torch

- Optional: Access to Databricks cluster or streaming data source (Kafka/socket/files)

#### Set environment variables as needed:

 	 export SPARK_HOME=/path/to/spark
 	 export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH


---

## Project Usage
To run an assignment locally:
	python "Assignment_1_Prineet Kaur Bhurji.py"

Or specify parameters (if applicable):
  	python "Assignment_3_Prineet Kaur Bhurji.py" --model_path models/model.pt --api_endpoint https://api.example.com

---

## Assignment Summaries
	•	Assignment 1 → [Batch data ingestion & Spark SQL queries]
	•	Assignment 2 → [Streaming ingestion and window aggregations]
	•	Assignment 3 → [Applying deep learning inference on streaming data with API integration]
