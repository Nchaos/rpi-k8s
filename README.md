# In Progress Project

# rpi-k8s
Configure and install bare-metal kubernetes on raspberry pis

An Ansible role for configuring raspberry pis for running docker and kubernetes.

## Requirements:
- Debian Lite OS Version running on the Raspberry Pis.

## Variables:
Variables are listed below along with default values:

Variable                          | Default value | Description/Comment
----------------------------------| --------------| -----------
**rpi_user**                      | nchao         | Name of the admin user to create
**rpi_user_password**             | password      | Password for the adnin user. Can overvide this via the commandline
**rpi_upgrade_system**            | true          | Whether or not to upgrade the system.
**rpi_remove_packages**           |               | List of packages to remove from the default system
**raspberry_pi_packages**         |               | List of packages to install
