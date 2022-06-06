# Instagram Clone

##### By Brian Jomo.

### It is a description of the Instagram Clone.

## Table of Content

+ [Description](#description)
+ [Installation Requirement](#Installation)
+ [Technology Used](#technology-used)
+ [Reference](#reference)
+ [Licence](#licence)
+ [Authors Info](#author-Info)


## Description

<p>This project involves creating a website that is similar to Instagram. Web visitors can create secure accounts, profiles, post images and view a variety of other user profiles and posts.</p>


## Installation

To gain acess to this application click on this link: https://github.com/BrianJomo/Instagram-clone

### Requirements

* Either a computer,phone,tablet or an Ipad.

* An access to the Internet.

### Installation Process

To access this application, type the following command in your terminal to have a local copy of the application.
```
https://github.com/BrianJomo/Instagram-clone.git
```
and for SSH, use the following command;
```
git@github.com:BrianJomo/Instagram-clone.git
```

### Setting up environment variables

Create a `.env` file and paste paste the following and fill where appropriate:
```
SECRET_KEY='**'
DEBUG=True
DB_NAME='****'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

Then run the following commands in the terminal then run the manage.py file in order to run the web application.

```
$ python3.8 -m venv --without-pip virtual

$ source virtual/bin/activate

$ curl https://bootstrap.pypa.io/get-pip.py | python

$ pip3 install -r requirements.txt 

$ python3.8 manage.py check

$ python3.8 manage.py makemigrations <installed app name>

$ python3.8 manage.py sqlmigrate <installed app name> 0001

$ python3.8 manage.py migrate

$ python3 manage.py runserver

```

To explore the features of this gallary website navigate to this link on your browser or just click on this link: 


## Technology Used
