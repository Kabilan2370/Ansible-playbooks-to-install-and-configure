## Ansible Infrastructure Setup on Ubuntu VM

**This project demonstrates how to use Ansible as a configuration management tool to install and configure Nginx, MySQL, PostgreSQL, and Docker Swarm on a remote Ubuntu VM.
It also covers database user creation, seeding sample data, log locations, and log rotation configuration and testing.**

## These are my file structures

![image](.2.png)

1. Using inventory.ini file to verify the ssh connection between the controller and worker.

      ansible -i inventory.ini workers -m ping

![image](.1.png)

3. 
