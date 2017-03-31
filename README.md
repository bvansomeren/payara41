payara
=========

Installs a simple Payara install that is ready for Dev use (Mostly to be used for Vagrant)
By default now uses maven\_artifact (Ansible module, maven not required)

Requirements
------------

Removed the dependency on a Java role, it is assumed you install Java

Role Variables
--------------

Please check the defaults/main.yml for all the current variables.

asadmin\_password: adminadmin  
install\_folder: /opt  
payara\_download\_url: https://s3-eu-west-1.amazonaws.com/payara.co/Payara+Downloads/payara.zip  
java\_max\_heap\_mb: 1578

Dependencies
------------

If you want to use Maven for downloading Payara you need to have lxml installed in Python on the receiving machine.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bvansomeren.payara41 }

Also, have a look at site.yml

License
-------

MIT

Author Information
------------------

