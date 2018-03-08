# poolagency
![poolagency logo](http://dashboard.tritontracking.com:5000/static/admin/resources/images/triton-logo.png)


At Pool Agency, we’re committed to the highest quality of service and reliability. Our modern approach to pool care includes the latest tracking technology, a GPS-tracked fleet of trucks, before and after photos of every job and the best mobile dispatch software in the industry. We carefully monitor each job to offer you instant feedback and keep quality high. From weekly maintenance and repair to remodeling, our one-stop shop offers services to both residential and commercial locations.


## Quick Start

### 1. Clone the repo
  ```
  $ git clone https://github.com/gate6/poolagency.git
  $ cd poolagency
  ```

### 2. Install the dependencies:
  ```
  $ pip install -r requirements.txt
  ```

### 3. Run the development server:


To start project in debug mode :

```shell
python src/api.py
```

To run project with nohup in forever mode:

```shell
nohup python src/api.py
```


### 4. Navigate to [https://localhost:5000](http://localhost:5000)


## Configuration


start your  project on the port you have mentioned in [`config.py`]
(https://github.com/gate6/poolagency/blob/master/src/config.py).
```shell
if not MODE or MODE is None:
   print('app is running on default mode')
   MODE = 'local'
```
In above code you have to mention a mode which you have to use as following
```shell
1.prd
2.staging
3.test
4.dev
5.local
```


In frontend we use angular & to start on the port you have mentioned in [`config.py`]
(https://github.com/gate6/poolagency/blob/master/src/static/admin/scripts/config.js).
```shell
MODE = 'localhost'
currEnvironment: MODE
   
```
In above code you have to mention a mode which you have to use as following
```shell
1.dev
2.test
3.staging
4.prd
5.localhost
```


Installation
================

First clone this repository or download code on machine where you would like to setup poolagency API.

1)Flask
----------
### Before we get started buildling with flask we need to setup our development environment. 

1. Install Python
2. Install flask 
 

### 1. Install Python

[Windows](http://timmyreilly.azurewebsites.net/python-flask-windows-development-environment-setup/)

[Mac](http://docs.python-guide.org/en/latest/starting/install/osx/)

[Linux](https://docs.aws.amazon.com/cli/latest/userguide/awscli-install-linux-python.html)



### 2. Install flask

Now we need [flask](http://flask.pocoo.org/) for our first website!

```
$ pip install flask
```


2)Flask-MySQLdb
----------

Flask-MySQLdb provides MySQL connection for Flask.

### Quickstart


First, install Flask-MySQLdb:
    
    $ pip install flask-mysqldb
    
Flask-MySQLdb depends, and will install for you, recent versions of Flask
(0.10.1 or later) and [mysqlclient](https://github.com/PyMySQL/mysqlclient-python). Flask-MySQLdb is compatible
with and tested on Python 2.7, 3.4, 3.5 and 3.6.we use here 2.7 in project.

Next, add a ``MySQL`` instance to your code:

```python
from flask import Flask
from flask_mysqldb import MySQL

app = Flask(__name__)
mysql = MySQL(app)
```

### Resources


- [Documentation](http://flask-mysqldb.readthedocs.org/en/latest/)
- [PyPI](https://pypi.python.org/pypi/Flask-MySQLdb)


Support
================
If you face any problem or issue in configuration or usage of poolagency  project as per the instruction documented above, Please feel free to communicate with poolagency Development Team.

