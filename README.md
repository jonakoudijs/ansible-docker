[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Docker Ansible Role
===================

Install Docker on Linux

Requirements
------------

This role does not have any requirements. However executing with sudo with `become: true` is required.

Role Variables
--------------

The following variables are set in `defaults/main.yml` and can be overwritten:
```
docker_apt_repo_url  # official Docker APT repository url
docker_apt_repo_key  # official Docker APT repository GPG key url
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
