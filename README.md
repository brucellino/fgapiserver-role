FutureGateway API server
=========

A role to deploy the web-facing API server of the Future Gateway. Developed specifically to run inside a container, so no init sorry for you.

Requirements
------------

uses git. needs some python.

Role Variables
--------------


Dependencies
------------

none

Example Playbook
----------------


    - hosts: api-servers
      roles:
         - { role:  brucellino.Future-Gateway-API-Server port: 8888 }

License
-------

Apache-2.0

Author Information
------------------

Bruce Becker
@brusisceddu
http://brucellino.github.io
