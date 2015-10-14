# flash-flask

```
date = "2015-02-10T02:11:02+08:00"
title = "Learn Flask"
authors = ["toph", "carl"]
```

In this guide, we’ll cover installing Flask and using it for the first time. Flask is a back end framework that we will be using alongside HTML and CSS. Contrary to to the front end, which is basically what the client sees, the back end consists of the internal mechanisms of a website, which handles stuff like input from the client.

## Installing Flask
To install Flask, we would be needing to 3 things:
1. Python 3
2. Pip3 - A tool that's used to manage packages written in Python
3. Virtual Environment - allows us to create Python environments that are isolated from one another. We will now create our own
virtual environment for a simple web app and install Flask in it.


Unix-based Operating Systems
---
On Ubuntu, Linux Mint, or other distributions that have `apt-get`, enter the command:
```
sudo apt-get install python3-pip
```
This will install pip3, a tool that's used to manage packages written in Python.

Then run the command:
```
sudo pip3 install virtualenv
```
Virtualenv allows us to create Python environments that are isolated from one another. We will now create our own
virtual environment for a simple web app and install Flask in it.

To install pip3 and virtualenv on Windows,
```
I have no idea how to install it on windows since I replaced it with ubuntu
```

Type these on the command line in order to make the virtual environment:
```
mkdir my_app
cd my_app
virtualenv venv
```
(note: the name my_app can be substituted with anything)

To enter the virtual environment, type:
```
. venv/bin/activate
```
Now install Flask:
```
sudo pip3 install flask
```
For Windows users, remove sudo.

And we're done!

Installing Flask in Windows
===
One main difference between Windows from Unix-based OS is that you need to edit your system environment variables in order to run python in the command prompt. Luckily, both the (1) system environment variables can already be updated and (2) pip can already be installed during the Python 3.5 installation. In order to accomplish that, you can do the following:

1. Download python 3.5 [here](https://www.python.org/downloads/).
Select custom installation.

2. Installing Virtualenv
```
python3 -m pip install virtualenv
```

## First Web App in Flask

asdfghjkl
