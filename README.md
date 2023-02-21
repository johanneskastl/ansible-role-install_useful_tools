![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_useful_tools/workflows/Ansible%20Lint/badge.svg)

install_useful_tools
=========

Install some useful tools like screen, emacs, vim, curl, netcat or git.

Requirements
------------

None.

Role Variables
--------------

- `useful_tools`: List of packages. Only a basic set is defined in `defaults/main.yml`, others are added on a per-distribution basis with correct names, only if available.

If you use this role on OpenWrt, you can decide if you want the `git` package to be installed (or not, to save space):

- `add_git_on_openwrt`: Boolean to decide if git is to be installed on OpenWrt (default: `true`)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.install_useful_tools' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
