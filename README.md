# Sports-Data-Analysis-Project-🏏

### Overview
This project focuses on analyzing the IPL 2017 cricket season data to extract meaningful insights. The data, sourced from multiple CSV files, includes detailed information on matches, players, teams, and ball-by-ball events. The analysis was conducted using PySpark and Databricks, leveraging custom schemas to ensure data accuracy and integrity.

<img width="1387" alt="Project Flow" src="https://github.com/user-attachments/assets/1a102d34-271b-4305-a68f-631693787b29">

### Project Goal
The primary goal of this project was to answer specific questions related to the IPL 2017 season, such as:

- Identifying the top-scoring batsmen.
- Calculating the average score per innings.
- Analyzing match outcomes and key player performances.

### Steps Involved
#### Data Collection:
- Loaded datasets from an S3 bucket, including Ball_by_ball.csv, Match.csv, Player_match.csv, Player.csv, and Team.csv.

#### Schema Definition:
- Defined custom schemas for each dataset to maintain the correct data types and prevent issues with schema inference.
  
#### Data Transformation:
- Performed various transformations using PySpark to derive insights such as total and average runs per innings, top performers, and match results.
  
#### SQL Views Creation:
- Converted transformed DataFrames into SQL Views within Databricks to enable SQL-based queries for deeper analysis.
  
#### Analysis & Visualization:
- Conducted SQL operations on the views to extract insights, visualize trends, and answer specific analytical questions.
  
#### Technologies Used
- Python
- PySpark
- Databricks
- AWS S3
- SQL
- Git

  ![most frequesnt dismissal](https://github.com/user-attachments/assets/cf27111b-4d76-4943-9c71-cb619b2f9aac)

  ![Team Performance after Toss winning](https://github.com/user-attachments/assets/4f5f3b2c-99c5-4228-98a4-fefb0860f353)


