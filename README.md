
# Phonepe Pulse Data Visualization and Exploration

* A User-Friendly Tool Using Streamlit and Plotly

## Problem Statement:
The Phonepe pulse Github repository contains a large amount of data related to various metrics and statistics. The goal is to extract this data and process it to obtain insights and information that can be visualized in a user-friendly manner.
The solution must include the following steps:
1. Extract data from the Phonepe pulse Github repository through scripting and
clone it..
2. Transform the data into a suitable format and perform any necessary cleaning
and pre-processing steps.
3. Insert the transformed data into a MySQL database for efficient storage and
retrieval.
4. Create a live geo visualization dashboard using Streamlit and Plotly in Python
to display the data in an interactive and visually appealing manner.
5. Fetch the data from the MySQL database to display in the dashboard.
6. Provide at least 10 different dropdown options for users to select different
facts and figures to display on the dashboard.

The solution must be secure, efficient, and user-friendly. The dashboard must be easily accessible and provide valuable insights and information about the data in the Phonepe pulse Github repository.

NAME: VISHALACHI

BATCH:DTM5

DOMAIN: Data Science

## Approach

1. Data extraction: Clone the Github using scripting to fetch the data from the
Phonepe pulse Github repository and store it in a suitable format such as CSV
or JSON.
2. Data transformation: Use a scripting language such as Python, along with
libraries such as Pandas, to manipulate and pre-process the data. This may
include cleaning the data, handling missing values, and transforming the data
into a format suitable for analysis and visualization.
3. Database insertion: Use the "mysql-connector-python" library in Python to
connect to a MySQL database and insert the transformed data using SQL
commands.
4. Dashboard creation: Use the Streamlit and Plotly libraries in Python to create
an interactive and visually appealing dashboard. Plotly's built-in geo map
functions can be used to display the data on a map and Streamlit can be used
to create a user-friendly interface with multiple dropdown options for users to
select different facts and figures to display.
5. Data retrieval: Use the "mysql-connector-python" library to connect to the
MySQL database and fetch the data into a Pandas dataframe. Use the data in
the dataframe to update the dashboard dynamically.
6. Deployment: Ensure the solution is secure, efficient, and user-friendly. Test
the solution thoroughly and deploy the dashboard publicly, making it
accessible to users.