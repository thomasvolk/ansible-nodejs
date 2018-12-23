Role Name
=========

Role for installing nodejs binaries.

[![Build Status](https://travis-ci.org/thomasvolk/ansible-nodejs.svg?branch=master)](https://travis-ci.org/thomasvolk/ansible-nodejs)

Role Variables
--------------

```
nodejs_version: 9.11.2
# raspberry pi: linux-armv6l
nodejs_arch: linux-x64
target_dir: /usr/local/lib
bin_dir: /usr/local/bin
```

Test
----

You have to install the tools first:
```
pip install docker ansible molecule
```

For tests just run molecule test:
```
molecule test
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-nodejs, x: 42 }

License
-------

Apache 2
