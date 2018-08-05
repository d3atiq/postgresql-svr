Role Name
=========

An Ansible role to install Postgres latest versions on Ubuntu.

Requirements
------------

The playbook must contain a variable to indicate the postgresql version required. The supported versions are indicated on PostgreSQL web site (https://www.postgresql.org/download/linux/ubuntu/).

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
      vars:
        postgresql:
          version: 9.6
      roles:
         - d3atiq.postgresql_svr

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
