Role Name
=========

Installation of tools than any self-respecting AWS command-line user loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* aws_cli_install: true
* aws_ecs_cli_install: true

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.aws, aws_ecs_cli_install: false }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
