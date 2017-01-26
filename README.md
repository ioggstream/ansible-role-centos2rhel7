Role Name
=========

Transform a CentOS7 into a RHEL7. 

Requirements
------------

No requirements.

Role Variables
--------------

No variables.

Dependencies
------------

No dependencies.

Example Playbook
----------------

Just add this role to servers that needs conversion.

    - hosts: servers
      roles:
         - { role: ioggstream.centos2rhel7 }

License
-------

BSD

Author Information
------------------

Roberto Polli <robipolli@gmail.com>
