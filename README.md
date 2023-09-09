# MySQL-and-Python
A small Python web app that allow users to create account, login, and make a bucket list.

This app is implemented using MySQL and Python. 
Copied from the tutorial http://code.tutsplus.com/tutorials/creating-a-web-app-from-scratch-using-python-flask-and-mysql--cms-22972


https://github.com/uym2/MySQL-and-Python.git

# Setup Steps:

## Create database & tables
- connect to DB server
- Run SQL Queries from sql_queries.txt file

## Setup BE server
- connect to BE server
- sudo apt update -y
- sudo yum install python3-pip -y
- yum install git -y
- git clone https://github.com/islamsalah2020/WebApp_Python_Flask_Mysql.git
- cd WebApp_Python_Flask_Mysql/
- python3 -m venv myvenv 
- source myvenv/bin/activate
- pip install -r requirements.txt
- edit DB Connections endpoint
- Python3 app.py

bucketlist.crh5uvoy63mv.us-east-1.rds.amazonaws.com

## Delete a venv with Pipenv
- pipenv --rm
- rm -r .venv



## ec2 scripts
- sudo apt update -y
- sudo yum install python3-pip -y
- mkdir myapp & cd myapp


## Activate virtual environment on windows
- dev-env\bin\activate.bat
- dev-env\Scripts\Activate.ps1
## Deactivate virtual environment windows
- deactivate
