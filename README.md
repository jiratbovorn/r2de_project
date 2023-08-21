<h1 align="center">Road to Data Engineer Project</h1>
<h2>Project Overview</h2>
<p>This project showcases the knowledge and skills gained from the comprehensive "Road to Data Engineer (R2DE 2.0)" course. The project aims to demonstrate proficiency in data engineering concepts, tools, and technologies by building an end-to-end data pipeline that covers various stages of data processing, integration, transformation, storage, and visualization.</p>

<h2>Course Concepts Applied</h2>
<p>Throughout the course, I acquired a solid foundation in SQL and Python, essential for data manipulation and analysis. I dived into fundamental data engineering concepts, including data extraction, data cleaning with Apache Spark, and data integration from diverse sources like REST APIs using Pandas.

I delved into cloud computing using Google Cloud Platform (GCP), learning how to create a basic Data Lake and process data efficiently. I automated data pipelines using Apache Airflow, orchestrating complex workflows and ensuring data consistency.

The project also explores advanced topics like data warehousing with Google BigQuery and data visualization using Google Data Studio.</p>

<h2>Technologies and Tools Used</h2>
<ul>
  <li>Python</li>
  <li>SQL</li>
  <li>Pandas</li>
  <li>Apache Spark</li>
  <li>Apache Airflow</li>
  <li>Google BigQuery</li>
  <li>Looker Studio</li>
</ul>

<h2>Workflow Overview</h2>

![Workflow Diagram](Picture/project%20flow.PNG)
<p align="center">Workflow diagram</p>

<h2> Workshop 1: Data Collection & Integration with Pandas</h2>
<p>Aggregated data from various sources such as MySQL databases and REST APIs, utilizing techniques like requests and Pandas.</p>

![Audible data](Picture/audible_data.PNG)
<p align="center">Example of audible data dataset</p>

![Audible transaction](Picture/audible_transaction.PNG)
<p align="center">Example of audible transaction dataset</p>

<h2> Workshop 2: Data Cleansing with Apache Spark</h2>
<p>I conducted preliminary Exploratory Data Analysis (EDA) and data handling using Spark on Google Colab. This involved initial data exploration to uncover insights and patterns, utilizing Spark's distributed processing capabilities for efficient data manipulation.</p>

![Final df](Picture/final_df.PNG)
<p align="center">Final dataset</p>


<h2> Workshop 3: Intro to Google Cloud & Google Cloud Storage</h2>
<p>I experimented with Cloud Storage to upload files which is output from previous workshop and explored basic command-line operations through Cloud Shell.</p>

![GCS](Picture/gcs.PNG)
<p align="center">Google Cloud Storage</p>

<h2> Workshop 4: Automate Data Pipeline with Airflow</h2>
<p>I created an automated data pipeline using Apache Airflow, integrating code from Workshop 1 and Workshop 3. This enabled me to orchestrate data collection and processing tasks, transforming them into an automated workflow. The result was an efficient and streamlined data pipeline that harnessed the power of automation for enhanced data management and processing.</p>

<h2> Workshop 5: Building a Big Data Warehouse with BigQuery</h2>
<p>I learned to use Google BigQuery and integrated it with Apache Airflow, a progression from Workshop 4. This integration enabled me to automate the transfer of data from Google Cloud Storage into Google BigQuery, streamlining the data pipeline process. Subsequently, I generated view from audible_data table within Google BigQuery to show only necessary columns for the visualization</p>

![Google BigQuery](Picture/bigquery.PNG)
<p align="center">Google BigQuery </p>


<h2> Workshop 6: Data Visualization with Looker Studio</h2>
<p></p>