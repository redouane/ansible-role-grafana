Ansible Role: Grafana
=====================

[![Build Status](https://travis-ci.org/redouane/ansible-role-grafana.svg?branch=master)](https://travis-ci.org/redouane/ansible-role-grafana)

Installs and configures grafana

Requirements
------------

None

Role Variables
--------------

```yaml

grafana_version: 2.1.3

#server
grafana_http_port: 3000
grafana_protocol: http

#security
grafana_admin_user: admin
grafana_admin_password: admin
grafana_secret_key: changeme
grafana_disable_gravatar: false


#users
grafana_allow_sign_up: true
grafana_allow_org_create: true
grafana_auto_assign_org: false
grafana_auto_assign_org_role: Viewer

#auth
grafana_auth_anonymous_enabled: false

#analytics
grafana_reporting_enabled: true

```

Dependencies
------------

None

License
-------

BSD