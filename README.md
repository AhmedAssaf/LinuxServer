# LinuxServer
Linux Server Configuration

## IP address
using Amazon Lightsail: 35.158.186.224

## URL
http://35.158.186.224.xip.io/

## software installed 
Apache
PostgreSQL
git 
pip
wsgi

## Dependencies/Pre-requisites
Python 2.6 or 2.7
Flask
Psycopg2
Requests
Oauth2client

## configurations made 
Enable only the  SSH (port 2200), HTTP (port 80), and NTP (port 123).
Create a new user account named grader.
Give grader the permission to sudo.
Create an SSH key pair for grader using the ssh-keygen tool.
Clone the below repo under /var/wwww/
```
git clone https://github.com/AhmedAssaf/Catalog-App.git
```
handle Wsgi conf to point to my application
disable the default conf
run the URL:  http://35.158.186.224.xip.io/
 
 
 ## License
 free to use

 ## Refrences
 Udacity Cource
 Some Session code
 Stackoverflow
 digitalocean
