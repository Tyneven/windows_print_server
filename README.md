# windows_print_server

Role to install print_server in windows.

Requirements
------------

Windows clients with WinRM configured.

Module Windows are required.

```bash
ansible-galaxy collection install ansible.windows
ansible-galaxy collection install community.windows
```

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
- hosts: windows
  roles:
    - role: windows_print_server
```          

License
-------

MIT License