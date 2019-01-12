# LinuxServer
Linux Server Configuration

## IP address
using Amazon Lightsail: 35.158.186.224

## URL
http://35.158.186.224.xip.io/

## software installed 
Apache <br />
PostgreSQL <br />
git  <br />
pip <br />
wsgi <br />

## Dependencies/Pre-requisites
Python 2.6 or 2.7 <br />
Flask <br />
Psycopg2 <br />
Requests <br />
Oauth2client

## configurations made 
Enable only the  SSH (port 2200), HTTP (port 80), and NTP (port 123). <br />
Create a new user account named grader. <br />
Give grader the permission to sudo. <br />
Create an SSH key pair for grader using the ssh-keygen tool. <br />
Clone the below repo under /var/wwww/ <br />
```
git clone https://github.com/AhmedAssaf/Catalog-App.git
```
handle Wsgi conf to point to my application <br />
disable the default conf <br />
run the URL:  http://35.158.186.224.xip.io/
 
 
 ## License
 free to use

 ## Refrences
 Udacity Cource <br />
 Some Session code <br />
 Stackoverflow  <br />
 digitalocean 
 
