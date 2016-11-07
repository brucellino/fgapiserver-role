[![Build Status](https://travis-ci.org/brucellino/fgapiserver-role.svg?branch=master)](https://travis-ci.org/brucellino/fgapiserver-role)  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

FutureGateway API server
=========

A role to deploy the web-facing API server of the Future Gateway. Developed specifically to run inside a container, so no init sorry for you.

Requirements
------------

uses git. needs some python.

Role Variables
--------------

TODO

Dependencies
------------

No other dependencies, but the API server needs a database and the Java GridEngine API connectors to be useful.

Example Playbook
----------------

- hosts: API-servers
      roles:
         - { role:  brucellino.Future-Gateway-API-Server port: 8888 }

License
-------

BSD

Author Information
------------------

Bruce Becker
http://brucellino.github.io
@brusisceddu
http://brucellino.github.io
