# ansibile_RaspberryPi_UbuntuServer
Ansible Playbook to Install Ubuntu Server on a Pi

This is just one way how to use Ansible to install Ubuntu Server on a Raspberry Pi.

###########################################
### Preconditions to use this Playbook: ###
###########################################
You need:
  -A Host System (e.g Ubuntu VM). In my case i use a VM on Unraid with PopOs! 
   The System has installed:
      -> Openssh
      -> Atom Editor
      -> Github Client (e.g GitKraken) 
      
  -one or mor Clients. This cut be VM's or in my case a Raspberry Pi
   The Pi need following Preconditions:
      -> needs a valid IP Adresse ( you must find the Pi in your network e.g. on you router) 
      -> The Raspberry Pi needs a File called ssh directly on the SD Card to active SSH. 
