Ansible Role: Chrome
=========
[![Build Status](https://travis-ci.org/cmprescott/ansible-role-chrome.svg?branch=master)](https://travis-ci.org/cmprescott/ansible-role-chrome)

Installs Google Chrome.

Requirements
------------

- **Ansible**: Tested on 1.9.0.1+
- **apt**: python-apt (http://docs.ansible.com/ansible/apt_module.html)
- or **dnf**: python-dnf (http://docs.ansible.com/ansible/dnf_module.html)

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
     - { role: cmprescott.chrome, become: yes }
```

License
-------

BSD

Author Information
------------------

Prescott Chris
