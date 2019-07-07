# Goal

The goal of this repository is to provide different examples of creating new roles for installation and 
configuration different software and also how to use galaxy roles.
To simplify testing you can use VirtualBox and Vagrant in order to start new virtual machine for testing
any ansible role in this repository

# VirtualBox & Vagrant installation
``` 
https://www.virtualbox.org/wiki/Downloads
https://www.vagrantup.com/docs/installation/

```

# Dirty hands
Start new virtualbox machine(ubuntu 19.04) with installed ansible by vagrant
``` 
% vagrant up
```
SSH to virtual machine
```
% vagrant ssh
```
Go to shared between host and virtual machine directory
```
% cd /vagrant_data/
```
