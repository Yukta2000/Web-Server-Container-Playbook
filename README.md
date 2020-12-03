# Web-Server-Container-Playbook
Configuring docker and launching docker container from httpd image
#This is an Ansible Playbook
Tested on RHEL Virtual Machine
#In code two yum repositories are configured with path of the dvd of RHEL that is mounted already , these provide some software required to download docker
#You can add your web pages in /web/ directory and to see if the page is being hosted type localhost:8080/webpage.html
#You can replace webpage.html with your file name that you have stored under /web/ in the VM on which container is running.
#For explaination of code refer this link: https://yuktachakravarty.medium.com/using-ansible-playbook-to-configure-docker-and-launch-docker-container-using-httpd-image-e33c424a2d2e
