# Common / Apt

A simpe Ansible role to manage basic packages and updates.

## Role Variables

None of the variables below are required.

| Variable                 | Default     | Comments |
| :---                     | :---        | :---     |
| `apt_upgrade`            | yes         | aptitude upgrade mode (no/full/dist) |
| `basic_packages`         | `vim, htop` | the default packages that will be installed on all systems |
| `addn_packages`          | -           | additional packages to be installed |
