Magerun Role
=========

Installs and configures [Magerun](http://magerun.net/)


Role Variables
--------------

```
magento_version: 1 | 2

magerun1_url: https://files.magerun.net/n98-magerun.phar
magerun2_url: https://files.magerun.net/n98-magerun2.phar

magerun_use_latest: true

magerun_path: /usr/local/bin/magerun
```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: cache
      roles:
         - { role: username.rolename, x: 42 }

Dependencies
------------
PHP

Usage
-----

```
# requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/magerun
#   version: master
#   name: magerun
```

License
-------

[MIT](LICENSE)