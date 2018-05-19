# ansible-vncserver

[![Build Status](https://travis-ci.com/dlampsi/ansible-vncserver.svg?branch=master)](https://travis-ci.com/dlampsi/ansible-vncserver)

Role for install and configure vncserver. Supported OS: `RedHat 6`, `RedHat 7`, `CentOS 6`, `CentOS 7`.

Using:

```yml
- name: 'Setup vncserver'
  hosts: ...
  vars:
    vnc_user: ...
    vnc_user_pass: ...
    vnc_display: ...
  roles:
    - ansible-vncserver
```
