install_useful_tools
=========

Install some useful tools like screen, emacs, vim, curl, netcat or git.

Requirements
------------

None.

Role Variables
--------------

`useful_tools`: List of packages. Only a basic set is defined in defaults/main.yml, others are added on a per-distribution basis with correct names, only if available.

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
