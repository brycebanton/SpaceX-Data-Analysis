# SpaceX-Data-Analysis

### Welcome! This is a Data Engineering project that pulls some SpaceX Data using api calls via Python!

#### To Note: 
When doing analysis of this data and looking at what columns there are, I found it to be lacking substance. With what I have, I demonstrated my Data Engineering skills, data analysis, and showed that I can write intermediate SQL (may not be complex due to the data I had). I've commented throughout this notebook on analysis summary and next steps I would like to do for this project.

### About: 
This analysis covers API pulls via JSON, Data Wrangling (Processing), DDL creation using SQLite3 in Python, and SQL executables commands for data analysis.

### Prereqs:
Jupyter notebook is used to help format and produce clean code. I will provide the library's below that is needed to run this notebook. Links to the data will also be provided so you can view the JSON format and the data that is within. You will also need to install SQlite. I went ahead and installed
SQLite studio for an easy option. This helps view the database, tables, and data.

### Librarys:
              import requests
              import pandas as pd
              import datetime
              import numpy as np
              import plotly.express as px
              import sqlite3
              import matplotlib.pyplot as plt

### Data Links: 
              "https://api.spacexdata.com/v4/rockets/"
              "https://api.spacexdata.com/v4/launchpads/"
              "https://api.spacexdata.com/v4/payloads/"
              "https://api.spacexdata.com/v4/launches/past"


### How to Run
To run this notebook it should be straight forward, you will need to make sure you SQLite (SQLite Studio for a nice interface) installed. The code within the notebook creates a database so the tables can be created and data can be stored. This database will stored as a file under your working directory. To view the database, open to where your Python working directory is set and search for a SQL file with the following name 'bbanton_interview'. This file will open up in your SQLite Studio with the database and the tables created.

### Schema Map
I used Dbeaver to create a easy and readible schema map of the database. This is a free tool and is community owned. The link to the download can be found here: https://dbeaver.io/
