ansible-role-proxy
=========

[![Build Status](https://travis-ci.org/ofsole/ansible-role-proxy.png?branch=master)](https://travis-ci.org/ofsole/ansible-role-proxy)

this module manages system level proxy in ubuntu, redhat and suse.

Requirements
------------

no.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: proxy
           server: 'http://myproxy.com'
           port: '8080'
           no_proxy:
             - localhost
             - 127.0.0.1
         

License
-------

BSD

Author Information
------------------

Elvis Cai
