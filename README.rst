Playbook Name
========

Install cherokee webserver, uwsgi and postgres. Configure and deploy django application.

Requirements
------------

Any pre-requisites that may not be covered within the playbook. 

Variables
-------------

The playbook sets these variables which can be overriden on the command line::


   vars:

    - repo: git@github.com/owner/repo.git

    - project: myproject

    - databases:
      { user: myproject_admin, database: myproject_db }

    - domain: myserver.example.com
    
    
    
    
Dependencies
------------

These are already included in the playbook and will be installed automatically:

- https://github.com/mirskytech-ansible/role-cherokee

- https://github.com/mirskytech-ansible/role-postgres


License
-------

MIT

Author Information
------------------

Andrew Mirsky

June 2, 2014

http://mirskytech.com
