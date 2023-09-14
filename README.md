# django-notes-app
This Git repository contains a Django web application with a Dockerfile created for DevOps purposes
**Requirements**
Python 3.9
Node.js
React
**#Installation**
Clone the repository

Build the app
docker build -t notes-app .
Run the app
docker run -d -p 8000:8000 notes-app:latest
Nginx
Install Nginx reverse proxy to make this application available

sudo apt-get update sudo apt install nginx
