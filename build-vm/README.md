# Steps to create, spin up and use a VM using vagrant:

 1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html).
 2. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 3. If you are using windows, make sure you have [Git](https://git-scm.com/downloads) or other similar software installed.
 4. paste this [vagrant] file in your system.
 5. Run vagrant up command while being in the same directory as your vagrant file. This will spin up and provision your new VM. 
    This will also automatically install JAVA and Ant into your new VM. 
 6. After successfully creating your new VM, you can either work on the VM directly(GUI) or use ssh on vagrant. To do this, you have to run 
    vagrant ssh command. 

# Login credentials:
 Username: vagrant
 Password: vagrant

# Acknoledgments:

The base box was taken from [https://vagrantcloud.com/rudolfochrist/boxes/ubuntu-desktop](https://vagrantcloud.com/rudolfochrist/boxes/ubuntu-desktop).
Configuration details were taken from [https://docs.vagrantup.com/v2/vagrantfile/machine_settings.html](https://docs.vagrantup.com/v2/vagrantfile/machine_settings.html)
