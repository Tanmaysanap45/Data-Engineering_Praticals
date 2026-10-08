Data Engineering Lab Portfolio
This repository contains a complete series of Data Engineering practical assignments (Practicals 1 through 10). It demonstrates a progressive journey from fundamental data manipulation and file parsing to building full-scale ETL pipelines, orchestrating workflows, and designing analytical data warehouses.

🛠️ Tech Stack & Tools
Languages: Python, SQL, JavaScript (MongoDB Shell)
Libraries: Pandas, NumPy, Scikit-learn, PySpark, Matplotlib, Requests
Databases: SQLite (Relational), MongoDB (NoSQL)
BI & Orchestration: Power BI, Apache Airflow
📂 List of Practicals
Practical 1: Data Parsing & CRUD Operations Scripts to parse multiple file formats (CSV, JSON, XML, HTML, TXT), detect data anomalies, perform regex pattern matching, and execute SQLite CRUD operations.
Practical 2: Business Intelligence ETL Extracting, transforming, and loading data using Power BI Query Editor (connecting to an OData feed, expanding nested tables, calculating derived columns, and building data models).
Practical 3: MongoDB Operations A NoSQL focus utilizing mongosh to perform single and multiple document insertions, along with formatted JSON data retrieval.
Practical 4: EDA & Data Preprocessing Using Pandas and Scikit-learn for Exploratory Data Analysis, outlier detection (Noise Elimination via IQR), and feature selection using Variance Thresholds.
Practical 5: API & Flat File Integration A Python pipeline that extracts live user data from a public REST API, cleans it, and merges it with a local CSV flat file for downstream processing.
Practical 6: Apache Airflow Orchestration Configuring a Directed Acyclic Graph (DAG) in Airflow to sequentially schedule and automate data extraction and logging tasks.
Practical 7: Advanced ETL & Incremental Loading A collection of pipelines addressing complex scenarios: combining multiple CSVs, flattening nested JSONs, validating data pre-load, isolating invalid records, and performing UPSERT incremental loads.
Practical 8: Big Data Processing with PySpark Distributed data processing techniques including schema definition, filtering, grouping, joining DataFrames, and removing duplicate records at scale.
Practical 9: E-Commerce Data Pipelines End-to-end Pandas and SQL pipelines simulating an e-commerce environment. Merges Customer, Order, Product, and Payment tables to generate lifetime revenue reports and handles historically arriving data.
Practical 10: Mini-Project (End-to-End Enterprise Pipeline) A capstone project simulating a complete retail data architecture. Features custom raw data generation, data cleansing, Star Schema data warehouse design (Fact & Dimension tables), and Power BI interactive dashboard reporting.
🚀 How to Run the Projects
Clone the repository:
git clone https://github.com/Rushi-Khairnar/data-engineering-practicals.git
cd data-engineering-practicals
Install Python dependencies: Make sure you have Python 3.x installed. Install the required libraries using pip:
pip install pandas numpy scikit-learn matplotlib requests pyspark
Running the Python Scripts: Most practicals are self-contained Python scripts. For example, to run the Mini-Project:
python mini_project_etl.py
Power BI / MongoDB:
Power BI: Open the .pbix files directly in Power BI Desktop to view the data models, Query Editor transformation steps, and interactive dashboards.
MongoDB: Reference the .md files for the exact queries to run inside your local mongosh environment.
