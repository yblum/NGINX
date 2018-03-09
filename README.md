# NGINX
# This is an automated deployment of an NGINX server running a puppet webpage locally on the CentOS machine
# The automation was done using puppet

# Requirements
# Virtualbox https://www.virtualbox.org/wiki/Downloads
# Vagrant https://www.vagrantup.com/

# Once you download both the Vagrantfile and the puppetcode directory use vagrant up

vagrant up 

# Once up just vagrant ssh into the box if needed

vagrant ssh

# Please note that the webpage will be served on page localhost:8000
# If you would like to serve it on 192.168.68.8 or any other IP than please comment-in the correct line in the Vagrantfile

