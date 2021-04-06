# Exploratory Learning Analytics Toolkit for Students (ELAS) - Web Server

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
TODO:

## Technologies
Project is created with:
* [Python](https://www.python.org/downloads/release/python-387/) (v3.8.7)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/) (v1.1.2)

## Setup
Step 1:- Download the latest version of Python from [Python official website](https://www.python.org/downloads/).

Step 2:- Install and activate virtualenv

Move inside to the project folder and open a terminal or cmd. Type the following commands to install virtualenv.

```
$ pip install virtualenv
$ pip install virtualenvwrapper-win
```

Step 3:- Create a virtual environment
```
$ virtualenv venv
```

Step 4:- Activate the virtual environment
```
$ .\venv\Scripts\activate
```

Step 5:- Install the python packages from the requirements file
```
$ pip install -r requirements.txt
```

Step 6:- Rename the file ```example.env``` to ```.env```.

Step 7:- Rename the file ```example.flaskenv``` to ```.flaskenv```.

Step 8:- Run the project either from a terminal or command prompt or powershell:

```
$ flask run
```

Web server should start running at localhost:5000.