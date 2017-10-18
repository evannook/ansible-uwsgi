uWSGI
=====

Install uWSGI packages

Role Variables
--------------

```yaml
uwsgi_version: UWSGI_VERSION
```

Dependencies
------------

- pylabs.python3

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: pylabs.uwsgi
  vars:
    uwsgi_version: UWSGI_VERSION
```

License
-------

MIT

Author Information
------------------

William Wu
