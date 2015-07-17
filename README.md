# Checkpoint

[![Build Status](https://travis-ci.org/OPIN-CA/ansible-role-checkpoint.svg?branch=master)](https://travis-ci.org/OPIN-CA/ansible-role-checkpoint)

http://www.opin.ca

An experimental virtual machine, only to be used by the brave. 

Build the Virtual Machine

Download this project and put it wherever you want.
Make copies of both of the example.* files, and modify to your liking:
Copy example.drupal.make.yml to drupal.make.yml.
Copy example.config.yml to config.yml.
Create a local directory where Drupal will be installed and configure the path to that directory in config.yml (local_path, inside vagrant_synced_folders).
Open Terminal, cd to this directory (containing the Vagrantfile and this README file).
[Mac/Linux only] Install Ansible Galaxy roles required for this VM: $ sudo ansible-galaxy install -r provisioning/requirements.txt --force
Type in vagrant up, and let Vagrant do its magic.
