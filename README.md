Debian-Docker
==============

Package Software into Standardized Units for Development, Shipment and Deployment

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-docker }

Tasks
-----

  - Install [Docker](http://www.docker.com/)
  - Install [Docker-compose](https://docs.docker.com/compose/)


License
-------

BSD
