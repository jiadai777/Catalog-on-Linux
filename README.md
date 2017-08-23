# Item Catalog on Amazon Lightsail

## This project is an Item Catalog prject previously by me and is now hosted on Amazon Lightsail server. It is public and can be visited by going to this IP address: 34.211.221.212 on your browser. This project is also meant to be graded by a Udacity grader, who will have access to my server remotely as a grader by using the private ssh key that I provide, and look over all the files and configurations I set up using the "grader" account.

## Project Information:
- IP Address: 34.211.221.212
- SSH port: 2200
- URL: 34.211.221.212
- softwares installed:
1. python 2.7
2. Flask
3. Postgresql
4. apache2
- third party sources:
1. [Steve Wooding](https://github.com/SteveWooding/fullstack-nanodegree-linux-server-config)
2. [Apache](http://flask.pocoo.org/docs/0.10/deploying/mod_wsgi/)
3. [Alias](https://httpd.apache.org/docs/2.4/mod/mod_alias.html#alias)
4. [PostgreSQL](http://docs.sqlalchemy.org/en/latest/core/engines.html)
- Location of SSH key on server: .ssh/authorized_keys

## For grader: please follow the steps below to ssh into the server as a grader.
1. On your local machine, download the grader SSH key I provided and save it in a .ssh folder.
2. Use the command to log in as grader from port 2200: ssh grader@34.211.221.212 -i ~/.ssh/(grader key) -p 2200
3. After logging in, your can explore all the files and configurations as a super user since grader has sudo access.
