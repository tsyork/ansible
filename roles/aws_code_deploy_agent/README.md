Role Name
=========

Installs and enables the AWS Code Deploy Agent. This role works with both init.d and systemd systems

Requirements
------------

* Ansible 2.0 or greater

Role Variables
--------------

This role takes no variables

Dependencies
------------

None

Example Playbook
----------------

     - name: codedeploy agent 
       hosts: app servers 
       roles:
         - aws_code_deploy_agent


License
-------

MIT

Author Information
------------------

Jonathan Davila
@DefionsCode on Twitter and GitHub
