ansible-role-meslolgs
=========

<p align="center">

<a href="https://github.com/iancleary/ansible-role-meslolgs/actions?query=workflow%3Aci" target="_blank">
    <img src="https://github.com/iancleary/ansible-role-meslolgs/workflows/CI/badge.svg" alt="CI workflow status">
</a>

<a href="https://github.com/iancleary/ansible-role-meslolgs/actions?query=workflow%3Arelease" target="_blank">
    <img src="https://github.com/iancleary/ansible-role-meslolgs/workflows/Release/badge.svg" alt="Release workflow status">
</a>

<a href="https://raw.githubusercontent.com/iancleary/ansible-role-meslolgs/main/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
</a>
</p>

This role installs the MesloLGS fonts according to [romkatv/powerlevel10k#fonts](https://github.com/romkatv/powerlevel10k#fonts).

> Only cloning via ssh is supported, at the current moment, as that was my initial use case.

Requirements
------------

None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

None
Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  user: unprivelaged
  roles:
    - role: iancleary.meslolgs
```

> This role doesn't need to be run as root, use whatever user you want to clone the repos as.

```yaml
- hosts: servers
  user: root
  roles:
    - role: iancleary.meslolgs
```

License
-------

[MIT](LICENSE)

Author Information
------------------

This role was created in 2023 by [Ian Cleary](https://iancleary.me).

Inspiration for the structure of this repo came from [Jeff Geerling](https://github.com/geerlingguy/ansible-role-nginx).
