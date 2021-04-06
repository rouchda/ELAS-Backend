# Exploratory Learning Analytics Toolkit for Students (ELAS) - Web Server

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Additional applications required for project](#Additional-applications-required)
* [Setup](#setup)

## General info
TODO:

## Technologies
Project is created with:
* [Python](https://www.python.org/downloads/release/python-387/) (v3.8.7)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/) (v1.1.2)
* [MongoDB Community Server](https://www.mongodb.com/try/download/community) (v4.4.4)

## Additional applications required
* [Postman](https://www.postman.com/downloads/)
* [Visual Studio Code](https://code.visualstudio.com/download) or [Pycharm Professional](https://www.jetbrains.com/de-de/pycharm/download/#section=windows)
* Mongo Compass (check the box to install when installing MongoDB Community Server)

## Setup
Step 1:- Download the latest version of Python from [Python official website](https://www.python.org/downloads/).

Step 2:- Download and install MongoDB Community Server from [MongoDB official website](https://www.mongodb.com/try/download/community).

Step 3:- Install and activate virtualenv

Move inside to the project folder and open a terminal or cmd. Type the following commands to install virtualenv.

```
$ pip install virtualenv
$ pip install virtualenvwrapper-win
```

Step 4:- Create a virtual environment
```
$ virtualenv venv
```

Step 5:- Activate the virtual environment
```
$ .\venv\Scripts\activate
```

Step 6:- Install the python packages from the requirements file
```
$ pip install -r requirements.txt
```

Step 7:- Rename the file ```example.env``` to ```.env```.

Step 8:- Rename the file ```example.flaskenv``` to ```.flaskenv```.

Step 9:- Run the project either from a terminal or command prompt or powershell:

```
$ flask run
```

Web server should start running at localhost:5000.