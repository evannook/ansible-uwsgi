uWSGI
=====

Install uWSGI packages

Role Variables
--------------

```yaml
uwsgi_version: UWSGI_VERSION
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: evannook.uwsgi
       uwsgi_version: UWSGI_VERSION
```

License
-------

MIT

Author Information
------------------

Evan Nook
