[![Ansible Galaxy](https://img.shields.io/badge/ansible%20galaxy-jonakoudijs.docker-blueviolet.svg)](https://galaxy.ansible.com/jonakoudijs/ansible_docker)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Docker Ansible Role
===================

Install Docker on Linux

Requirements
------------

This role needs `pip` to be installed. Besides that executing the role as root with `become: true` is required.

Role Variables
--------------

The following variables are set in `defaults/main.yml` and can be overwritten:
```
docker_repo  # Use official Docker package repository
```

Dependencies
------------

This role does not have any dependencies.

Example Playbook
----------------

Installing Docker:
```
- hosts: servers
  roles:
     - docker
```

License
-------

[MIT license](LICENSE)

Author Information
------------------

Originally created by [Jona Koudijs](https://www.jona.io).
