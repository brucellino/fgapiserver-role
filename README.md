[![Build Status](https://travis-ci.org/brucellino/fgapiserver-role.svg?branch=master)](https://travis-ci.org/brucellino/fgapiserver-role)  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

FutureGateway API server
=========

A role to deploy the web-facing API server of the Future Gateway. Developed specifically to run inside a container, so no init sorry for you.

Requirements
------------

uses git. needs some python.

Role Variables
--------------

There are several variables which are kept in `vars/main.yml`. The description of the vars can be found in [FutureGateway](https://githu.com/FutureGateway/fgAPIServer) ([hopefully](https://githu.com/FutureGateway/fgAPIServer/issues/9) )

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

Apache-2.0 Copyright C.S.I.R. Meraka Institute

Author Information
------------------

Bruce Becker
@brusisceddu
http://brucellino.github.io
