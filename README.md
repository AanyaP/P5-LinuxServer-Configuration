# LinuxServer-Configuration
Linux Server Configuration
-----------------------------------------------------------------------

A baseline installation of a Linux distribution on a virtual machine and prepared it to host web applications, to include installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.

Public IP address:  52.38.161.182

SSH port: 2200

Application URL: http:// 52.38.161.182/

Amazon EC2 Instance's public URL: http://ec2-52-38-161-182.us-west-2.compute.amazonaws.com/

Instructions: 
-----------------------------------------------------------------------


Passphrase for grader is set to be: DarthVader

password for grader is set to be: DarthVader

All the rest passwords are set to be: grader

Installed packages:
-----------------------------------------------------------------------

Package Name:                                                        Description

finger:	Displays information about the system users

ntp:	For synchronizing time over a network

apache2:	HTTP Server

libapache2-mod-wsgi:	For hosting Python applications on Apache2

postgresql:	Database server

git:	Version control system tools

python-setuptools:	Includes easy-install to facilitate installing Python packages

sqlalchemy:	ORM and SQL tools for Python

flask:	Microframework for website

python-psycopg2:	PostgreSQL adapter for Python

oauth2:	Authorization framework for using third-party login

google-api-python-client:	Google API for OAuth login


Summary of file and configuration changes:
-----------------------------------------------------------------------
⦁	New user named "grader" is added

⦁	Granted grader the sudo permissions.

⦁	Installed packages were updated.

⦁	SSH port was changed from 22 to 2200.

⦁	UFW configured to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).

⦁	Local timezone changed to UTC.

⦁	Apache and Python WSGI were installed.

⦁	Git installed and restaurant menu application set up on server.

⦁	PostgreSQL left with default settings to not allow remote connections.

⦁	User called 'catalog' added to PostgreSQL database for app connection.

References:
-----------------------------------------------------------------------

⦁	https://docs.google.com/document/d/1J0gpbuSlcFa2IQScrTIqI6o3dice-9T7v8EDNjJDfUI/pub?embedded=true

⦁	https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-12-04

⦁	https://discussions.udacity.com/t/issues-loading-postgresql-database/47523

⦁	http://stackoverflow.com/

⦁	https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server

⦁	https://www.digitalocean.com/community/tutorials/how-to-setup-a-firewall-with-ufw-on-an-ubuntu-and-debian-cloud-server

www.google.com

⦁	www.github.com

https://discussions.udacity.com/t/project-5-resources/28343
