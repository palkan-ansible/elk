ElasticSearch + Kibana + Logstash
========

Installs ELK stack.
Built on top of [this role](https://github.com/bakhti/ansible-elk).

Installation
--------------

`ansible-galaxy install palkan.elk`

Role Variables
--------------

See `defaults/main.yml`.

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - palkan.elk
```