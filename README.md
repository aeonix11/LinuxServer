# LinuxServer

##Ip address and ssh port : 35.176.82.86 port 2200

##Address : http://35.176.82.86/home/

##Summary of software installed and configuration changes:

Installed
+python pip
+Apache
+Git
+Virtual Environment
+flask
+wsgi python
+jinja2
+markupsafe
+httplib2
+oauth2
+rsa
+six
+oauth2client
+urllib3
+pyasn1-modules
+postgresql
+sqlalchemy
+psycopg2
+requests


-Configured firewall to allow port 80, 2200 and 123
-Configured apache to run project
-Configured postgresql to run database for project
-Configured the local timezone to UTC
-Changed the SSH port to 2200
-Updated all currently installed packages
-Created new user Grader
-Set SSH login keys
-Configured virtual host to run project

##Third party resources used:
+https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
+https://www.postgresql.org/docs/9.1/static/
