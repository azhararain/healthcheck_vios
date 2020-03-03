Role Name
=========

HEALTHCHECK_VIOS role is designed to check values of various VIOS parameters against the best practices recommended values (Can be modified in defaults/main.yml). If any value does not match to the desired value the output shows this.

Requirements
------------

This role is only for IBM VIOS.

Role Variables
--------------

Desired values of variables can be set in default/main.yml

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: vios
  gather_facts: no
  remote_user: ansible
  roles:
    - healthcheck_vios

License
-------

BSD

Author Information
------------------

Written by Azhar Ali of IBM Systems Lab Services MEA
Provide feedback, suggestion or input at azharali@pk.ibm.com
Feel free to request me for any new feature you believe should be added to this playbook
Usage notes: This playbook NOT OFFICIALLY SUPPORTED. No warrantee is given or implied, and you cannot obtain help with it from IBM.

Credits
------------------

Credits: v0.1 Fredrik Lundholm's (Power Implementation Quality Standard document) to identify the parameters to check as a baseline
