payara
=========

Installs a simple Payara install that is ready for Dev use (Mostly to be used for Vagrant)

Requirements
------------

Removed the dependency on a Java role, it is assumed you install Java

Role Variables
--------------

Please check the defaults/main.yml for all the current variables.

asadmin_password: adminadmin  
install_folder: /opt  
payara_download_url: https://s3-eu-west-1.amazonaws.com/payara.co/Payara+Downloads/payara.zip  
java_max_heap_mb: 1578

Dependencies
------------


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

