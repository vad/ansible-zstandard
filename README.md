An ansible role to install zstandard on Ubuntu machines.

## How to use it

```
- name: setup zstd on local machine
  hosts: localhost
  become: yes
  roles:
    - ansible-zstandard
```
