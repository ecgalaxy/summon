ECGALAXY summon role
==================

Installs summon - https://cyberark.github.io/summon/

Requirements
------------

* tar
* wget

Role Variables
--------------

See defaults.

Dependencies
------------

* ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.common_packages
        - ecgalaxy.summon

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
