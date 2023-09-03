# MySQL-and-Python
A small Python web app that allow users to create account, login, and make a bucket list.

This app is implemented using MySQL and Python. 
Copied from the tutorial http://code.tutsplus.com/tutorials/creating-a-web-app-from-scratch-using-python-flask-and-mysql--cms-22972


https://github.com/uym2/MySQL-and-Python.git

pip install -r requirements.txt
create database & tables

# create venv
python3 -m venv myvenv

# Activate virtual environment on Linux
source .venv/bin/activate

# Activate virtual environment on windows
# From command prompt
dev-env\bin\activate.bat
# From power shell
dev-env\Scripts\Activate.ps1

# Deactivate virtual environment Linux
source bin/deactivate

# Deactivate virtual environment windows
deactivate

# Delete a venv with Pipenv
pipenv --rm
rm -r .venv

#ec2 scripts
sudo apt update -y
sudo yum install python3-pip -y

mkdir myapp & cd myapp
python3 -m venv myvenv 
yum install git -y