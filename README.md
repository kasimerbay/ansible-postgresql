Role Name
=========

PostgreSQL Installation & DB Creation Role

Requirements
------------

Tested On 
* **Fedora38**
* More Coming soon...

Role Variables
--------------

application_name: {{ application_name }}

postgresql_db_encoding: {{ postgresql_db_encoding }}

postgresql_version: {{ postgresql_version }}

postgresql_db_user="{{ application_name }}_owner"

postgresql_db_name: "{{ application_name }}_db"

postgresql_db_password: {{ postgresql_db_password }}


License
-------

Under ALTAY Licence


BSD

Author Information
------------------

[@kasimerbay](https://kasimerbay.github.io)
