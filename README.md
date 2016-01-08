
### REQUIRED ###

# Install Virtualbox
sudo apt-get install virtualbox

# Install Vagrant
sudo apt-get install vagrant

# Add vagrant box ubuntu/trusty64
vagrant box add ubuntu/trusty64


### INSTALLATION ###
git clone https://github.com/nicolastorre/VM-Vagrant.git

cd portfolio

### START ###
vagrant up

### WEBSITE ###
Add to /etc/hosts: 192.168.33.22   app.local

Visit: http://app.local/

### END ###
vagrant suspend OR vagrant halt
