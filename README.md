ECGALAXY summon role
==================

Installs summon - https://cyberark.github.io/summon/

Requirements
------------

- The `unzip` command, which can be provided by the `ecgalaxy.common_packages` role.

Role Variables
--------------

See defaults.

Dependencies
------------

- optional: ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.common_packages
        - ecgalaxy.summon

One-liner
---------

    bash <(curl -s https://code.europa.eu/-/snippets/1/raw/main/ansible-role.sh) ecgalaxy.summon

See [ansible-role](https://code.europa.eu/-/snippets/1) for instructions.

Please verify the script integrity first.

Upgrading
---------

In order to upgrade, reexecute this Ansible role after a new version has been released.

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
