sthysel.neovim
===

Install and configure neovim with common plugins and their
dependencies.

Usage
===

```
 ansible-playbook nvim.yml -i inventory -K
```

Inventory
===

A inventory file containing something like:
```
localhost  ansible_connection=local 
```

Playbook 
===

A playbook (nvim.yml) like:
```
---
- hosts: localhost
  roles:
    - sthysel.neovim

```
