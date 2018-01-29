Install tmux [![Build Status](https://travis-ci.org/shengyou/ansible-role-tmux.svg?branch=master)](https://travis-ci.org/shengyou/ansible-role-tmux)
=========

安裝 tmux。

Requirements
------------

* ansible >= 2.4
* python >= 2.6

Dependencies
------------

none.

Example Playbook
----------------

```
- name: install_tmux.yml
  hosts: myhost
  gather_facts: yes
  become: yes

  roles:
    - install_tmux
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
