# flash-flask

+++
date = "2015-02-10T02:11:02+08:00"
title = "Learn Flask"
authors = ["toph", "carl"]

+++

In this guide, we’ll cover installing Flask and using it for the first time. Flask is a back end framework that we will be using alongside HTML and CSS. Contrary to to the front end, which is basically what the client sees, the back end consists of the internal mechanisms of a website, which handles stuff like input from the client.

## Installing Flask

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

## Installing Flask in Windows

## First Web App in Flask

asdfghjkl
