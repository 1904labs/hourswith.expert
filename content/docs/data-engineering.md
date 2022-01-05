---
author: "Kit Menke"
date: 2022-01-03
title: Data Engineering Introduction
weight: 10
---

## Data Engineering Introduction

First there was files. Files as far as the eye could see. Data in CSV and XML. Then Excel came along. If you were fancy you had mainframes.

Then came the relational database renaissance. Everyone writes SQL and puts all their data in Oracle, MySQL, PostgreSQL, or SQL Server. 

Next people wanted to consolidate all their data into a Data Warehouse. MPP platforms like Teradata, Netezza, and Oracle DW.

Hadoop burst onto the scene with cluster computing. Hadoop distributed file system. Map Reduce

Cloud offered a new way with managed services. Separation of storage and compute.


MPP - Massively Parallel Processing
SQL - Structured Query Language
NoSQL - Literally No SQL or “Not Only SQL”. Examples include key/value stores like Redis, wide column dbs like Cassandra and HBase.


Volume - The quantity of generated and stored data. 
Big Data is typically when you have so much data you can’t store/process it effectively on one machine

Variety - The type and nature of the data.
Example: files like CSV, structured data in databases, audio, videos, sensor readings, logs

Velocity - the speed at which the data is generated and processed 
Batch (once a day, import a file into the database), Streaming 24/7 process transactions looking for fraud

Variability - Inconsistency of the data set can hamper processes to handle and manage it.
Do the values in the dataset mean the same thing? Example: free text notes field where someone enters a value, email addresses, names

Veracity - The quality of captured data can vary greatly,
Trustworthiness of the data 
