mysql_DBroles
=========

This role install mysql DB, start, create DB and create db user. 

Requirements
------------

Debian 10 buster/Ubuntu


Role Variables
--------------

dbuser, password, DB name

Dependencies
------------

check for python roles under my roles to install dependecies

Example Playbook
----------------

  name: Deploy a web application
  hosts: db_web_server_for_flask
  roles:
    - python
    - mysql_DBrole
    - flask_webrole
