![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_useful_tools/workflows/Ansible%20Lint/badge.svg)

install_useful_tools
=========

Install some useful tools like screen, emacs, vim, curl, netcat or git.

Requirements
------------

None.

Role Variables
--------------

`useful_tools`: List of packages, currently SLES/openSUSE-based.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: johanneskastl.install_useful_tools }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
