# ansible-docker

Ansible role for install docker-compose and docker on CentOS/Ubuntu hosts.

Usage:

Set compose version (default is 1.24.0):
```
vars:
  compose_version: 1.24.0
```

For install docker-compose and docker
--tags=install,configure

For configure host for docker:
--tags=configure

For reload docker service:
--tags=reload
