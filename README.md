Ansible role: Template
======================

Template for an Ansible role.

Based on:

```bash
molecule init role template
```

Requirements
------------

None.

Role Variables
--------------

See `defaults/main.yml`:

```yaml
some_variable: some_value
```

A really important variable.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all

  vars:
    some_variable: some_value

  roles:
    - template
```

License
-------

MIT

Author Information
------------------

ttirtia
