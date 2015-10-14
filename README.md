# flash-flask: get started with flask

```
date = "2015-02-10T02:11:02+08:00"
title = "Learn Flask"
authors = ["toph", "carl"]
```

In this guide, we’ll cover installing Flask and using it for the first time. Flask is a back-end framework that we will be using alongside HTML and CSS. Contrary to to the front end, which is basically what the client sees, the back end consists of the internal mechanisms of a website, which handles stuff like input from the client.

After completing this tutorial, you will be able to:
* Number 1
* Number 2
* Number 3

## Installing Flask

To install Flask, we would be needing to 3 things:
1. Python 3 - a widely used general-purpose, high-level programming language.
2. pip - a tool that's used to manage packages written in Python
3. Virtual Environment (Virtualenv)- allows us to create Python environments that are isolated from one another. We will now create our own
virtual environment for a simple web app and install Flask in it.

To learn more about one of the best programming language, check out [Python's Website](https://www.python.org/).

For a  thorough beginner-level explanation for pip and Virtualenv, you could check out this awesome [article](http://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/).

For Unix-based Operating Systems
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

And we're done! Let's proceed to our First Web App in Flask!

For Windows
===
One main difference between Windows from Unix-based OS is that you need to edit your system environment variables in order to run python in the command prompt.

Luckily, both the (1) system environment variables can already be updated and (2) pip can already be installed during the Python 3.5 installation. In order to accomplish that, you can do the following:

1. Quick-Guide: Python 3.5 Installation
    For a thorough guide, you can click this [link](google.com).

  a. Download python 3.5 [here](https://www.python.org/downloads/).

  b. Run (as administator) the downloaded exe file.

  c. Select `Customize Installation`

  d. In Optional Feature, tick the checkbox `pip`. Click `next`.

  e. In Advanced Options, tick the checkbox `Add Python to environment variables`. Click `Install`

2. Pip Installation
  If you did Step 1, then you don't need to do this.

  Else if you have installed Python before but didn't decide to install pip, then do the following:

  Enter the following in our command line:
```
python -m easy_install pip
```
  The command above makes use of easy_install, a primitive package manager (same as pip) that is installed automatically when you install python.


3. Installing Virtualenv

  In your command line, enter:
```
python -m pip install virtualenv
```

## First Web App in Flask

asdfghjkl
