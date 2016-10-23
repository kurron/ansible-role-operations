Role Name
=========

Installation of tools than any self-respecting Operation person loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* operations_sysdig_install: true
* operations_loggly_install: true
* operations_loggly_tag: host-of-interest
* operations_loggly_token: 00000000-0000-0000-0000-00000000000d@00000
* operations_datadog_install: true
* operations_datadog_api_key: 0000000000000000000000000000000

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.operations, operations_datadog_api_key: 1234, operations_loggly_token: 1234@12345 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
