# aview-server

This is a server side component of the aview software. It manages the information storage and retrieval between the client and the database. 

# License

The code in this repository is licensed under CC-BY-SA unless otherwise noted. Please follow the link for more details.
https://creativecommons.org/licenses/by-sa/4.0/legalcode

# Functionality

* Does the authentication and authorization for logging into aview client
* Does the functionality of adding/retrieving/removing various info needed to run aview client 

# Installation
* Supported platforms: Ubuntu and Windows server
* Install Apache Tomcat 7.0.41 with jre 7
* Deploy the war files from this project to webroot of tomcat and restart the server.
* Ensure the mysql.properties point to the correct database server with the appropriate user credentials
* To verify that everything is working, please point the aview client to this server and check if you can login to the aview platform client
