Ansible role for HSTR
=========

This role installs the [HSTR](https://github.com/dvorka/hstr) command search shell history suggest box.

While HSTR is available in most package repositories of a lot of modern distributions, some older (but still supported) releases don't have it.
This role adds the repositories required in these cases. Otherwise, it just installs HSTR using the package manager.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
---

- hosts: workstations
  tasks:
    - name: 'Install hstr'
      ansible.builtin.include_role:
        name: '0x4d4c.hstr'
```

License
-------

BSD-3-Clause

Author Information
------------------

0x4d4c
