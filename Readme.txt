Ansible Playbook:

Defines the automation tasks required to set up the webserver.
Includes tasks for installing Apache, configuring the service, and deploying a custom HTML page.
Ansible Role:

Name: webserver
Purpose: Encapsulates the tasks needed to install and configure the webserver.
Tasks:
Install Apache HTTP Server.
Start and enable Apache service.
Deploy a custom index.html page using a Jinja2 template.
Inventory File:

Specifies the target servers for deployment.
Contains server IPs and SSH user details.
Templates:

index.html.j2: Jinja2 template for the webserver's homepage.