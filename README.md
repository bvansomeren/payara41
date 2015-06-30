payara
=========

Installs a simple Payara install that is ready for Dev use (Mostly to be used for Vagrant)

Requirements
------------

CentOS 7; Will automatically install OpenJDK 8

Role Variables
--------------

Please check the defaults/main.yml for all the current variables.
asadmin_password: adminadmin
install_folder: /opt
payara_download_url: https://s3-eu-west-1.amazonaws.com/payara.co/Payara+Downloads/payara.zip
java_max_heap_mb: 1578

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bvansomeren.payara41 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
