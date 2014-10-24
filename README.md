boundary-vagrant
================

Example Vagrantfile that creates a Ubuntu 12.04 LTS virtual machine.

## Requirements
- Vagrant (http://www.vagrantup.com/downloads.html)
- Virtualbox (https://www.virtualbox.org/wiki/Downloads)

## Instructions

### Startup

1. Start the virtual machine
     ```bash
     $ vagrant up
     ```
2. Wait until the virtual machines starts and completes provisioning
3. To login onto the host:
     ```bash
     $ vagrant ssh
     ```

### Shutdown
Completely destroys the VM and its state, but it also frees up all the disk usage associated with the VM instance.

1. Stop and destroy the virtual machine
     ```
     $ vagrant destroy
     ```

