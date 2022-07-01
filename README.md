# Ansible Role: Gimp
[![CI](https://github.com/skaary/ansible-role-gimp/actions/workflows/ci.yml/badge.svg?branch=main&event=push)](https://github.com/skaary/ansible-role-gimp/actions?query=workflow%3Ci)

An Ansible Role that installs [Gimp](https://www.gimp.org/) on Linux.

## Requirements

None

## Dependencies

None

## Installation

Download the role directly from git by typing into your terminal:

```bash
ansible-galaxy install git+https://github.com:skaary/ansible-role-gimp.git
```

or

```bash
ansible-galaxy install git+https://github.com:skaary/ansible-role-gimp.git,,gimp
```

to change the installed role name from _ansible_role_gimp_ to just _gimp_.

Alternatively, install the role via a _requirements.yml_ file, e.g. when installing multiple roles at once. See [ansible galaxy documentation](https://galaxy.ansible.com/docs/using/installing.html#installing-multiple-roles-from-a-file) for more information.

## Example Playbook

```yaml
- hosts: all
  roles:
    - ansible-role-gimp
```
