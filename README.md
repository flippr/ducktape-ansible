README
======

*NOT MEANT FOR PRODUCTION SERVICES*: This deployment is to setup the basic requirements of a Ducktape.php deployment.  The passwords used are insecure and you *MUST* change them to have a secure production service.

Documentation
------------

The following are required or used by the ducktape-ansible script

1. Download Required Packages: python-pip, git, python-dev, python-mysqldb, sudo
2. Add ducktape user to sudoers file (visudo, copy root's permissions and replace 'root' with 'ducktape')
