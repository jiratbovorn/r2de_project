<h1 align="center">Road to Data Engineer Project</h1>
<h2>Project Overview</h2>
<p>This project showcases the knowledge and skills gained from the comprehensive "Road to Data Engineer (R2DE 2.0)" course. The project aims to demonstrate proficiency in data engineering concepts, tools, and technologies by constructing a comprehensive end-to-end data pipeline that covers various stages of data processing, integration, transformation, storage, and visualization.</p>

<h2>Course Concepts Applied</h2>
<p>Throughout the course, I acquired a solid foundation in SQL and Python, essential for data manipulation and analysis. I explored fundamental data engineering principles, including data extraction, data cleansing with Apache Spark, and data integration from various sources such as REST APIs using Pandas.

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
<p align="center"><em>Workflow diagram</em></p>
<br>

<h2> Workshop 1: Data Collection & Integration with Pandas</h2>
<p>Aggregated data from various sources, including MySQL databases and REST APIs, utilizing techniques such as requests and Pandas.</p>

![Audible data](Picture/audible_data.PNG)
<p align="center"><em>Example of audible data dataset</em></p>
<br>

![Audible transaction](Picture/audible_transaction.PNG)
<p align="center"><em>Example of audible transaction dataset</em></p>
<br>


<h2> Workshop 2: Data Cleansing with Apache Spark</h2>
<p>Performed initial Exploratory Data Analysis (EDA) and data manipulation using Spark on Google Colab. This included exploratory data mining to unveil insights and patterns.</p>

![Final df](Picture/final_df.PNG)
<p align="center"><em>Final dataset</em></p>
<br>


<h2> Workshop 3: Intro to Google Cloud & Google Cloud Storage</h2>
<p>Experimented with Cloud Storage for file uploads and explored fundamental command-line operations using Cloud Shell.</p>

![GCS](Picture/gcs.PNG)
<p align="center"><em>Google Cloud Storage</em></p>
<br>

<h2> Workshop 4: Automate Data Pipeline with Airflow</h2>
<p>Created an automated data pipeline using Apache Airflow, integrating code from Workshop 1 and Workshop 3. This enabled me to orchestrate data collection and processing tasks, transforming them into an automated workflow. The result was an efficient and streamlined data pipeline that harnessed the power of automation for enhanced data management and processing.</p>
<br>

<h2> Workshop 5: Building a Big Data Warehouse with BigQuery</h2>
<p>Learned to use Google BigQuery and integrated it with Apache Airflow, a progression from Workshop 4. This integration enabled me to automate the transfer of data from Google Cloud Storage into Google BigQuery, streamlining the data pipeline process. Subsequently, I generated view from audible_data table within Google BigQuery to show only necessary columns for the visualization</p>

![Google BigQuery](Picture/bigquery.PNG)
<p align="center"><em>Google BigQuery</em></p>
<br>


<h2>Workshop 6: Data Visualization with Looker Studio</h2>
<p>Developed data visualization dashboard using Looker Studio, using data derived from BigQuery. The dashboard assists the product and marketing teams in their decision-making processes.</p>
<br>

![Dashboard1](Picture/dashboard_1.PNG)
<p align="center"><em>Dashboard 1</em></p>

<p>Presented summarized information from Dashboard 1 includes:</p>
<ul>
  <li>Total revenue by country</li>
  <li>Total customers by country</li>
  <li>Number of transactions in each country</li>
  <li>Bestselling books</li>
  <li>Bestselling book categories</li>
</ul>
<br>

![Dashboard2](Picture/dashboard_2.PNG)
<p align="center"><em>Dashboard 2</em></p>

<p>Presented summarized information from Dashboard 2 includes:</p>
<ul>
  <li>Book title and revenue based on criteria (<em>min_revenue</em>)</li>
</ul>
<br>

<h2>Conclusion</h2>
<p>By completing this project, I have not only demonstrated practical proficiency in data engineering but also showcased the ability to apply cutting-edge technologies to solve real-world data challenges. The project stands as a testament to the comprehensive learning journey undertaken during the "Road to Data Engineer" course.

This project reflects my dedication to mastering data engineering skills, contributing to the broader data engineering community, and fostering a deeper understanding of the intricacies involved in building robust and efficient data pipelines.</p>

<h2>Certificate</h2>
<p>With the successful completion of the 'Road to Data Engineer' course, I proudly showcase my certificate of achievement.</p>
<br>

![Certificate](Certificate.png)
<p align="center"><em>Road to Data Engineer Certificate</em></p>

