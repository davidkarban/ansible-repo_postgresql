Repo_postgresql
=========

Role install postgresql yum repository on RHEL and clones. You can pick what version you want install.

Role Variables
--------------

repo_postgresql_version: Version of postgresql to install. Available version to be found on http://yum.postgresql.org/

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: repo_postgresql, repo_postgresql_version: '9.2' }

License
-------

GPLv3

Author Information
------------------

email: david@karban.eu

github: davidkarban

web: www.karban.eu

