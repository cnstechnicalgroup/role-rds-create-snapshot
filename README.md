Role: cns.rds-create-snapshot
========

This role creates an RDS snapshot.

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name               | Default |                                                        |
|--------------------|---------|--------------------------------------------------------|
| ---                |   ---   ||

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Created by Sam Morrison [@samcns](https://www.twitter.com/samcns)

Examples
--------

```yaml
---
- name: cns.rds-create-snapshot role test
  hosts: all
  roles:
    - { role: cns.rds-create-snapshot, tags: ["rdscreatesnapshot"] }
```
