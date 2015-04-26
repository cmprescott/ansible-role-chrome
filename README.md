Ansible Role: Chrome
=========

Installs Google Chrome. 

Requirements
------------

- **Ansible**: Tested on 1.5.4+
- **apt**: python-apt (http://docs.ansible.com/apt_repository_module.html)

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: clients
  roles:
     - { role: cmprescott.chrome, sudo: Yes }
```

License
-------

BSD

Author Information
------------------

Prescott Chris