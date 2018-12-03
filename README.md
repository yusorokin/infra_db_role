[![Build Status](https://travis-ci.org/yusorokin/infra_db_role.svg?branch=master)](https://travis-ci.org/yusorokin/infra_db_role)

Наименование роли
=========

Роль для установки и настройки MongoDB

Переменные роли
--------------

* `mongo_bind_ip` - внутренний ip-адрес;
* `mongo_port` - порт для прослушивания.

Пример Playbook-а
----------------

```
    - hosts: all
      roles:
         - infra_db_role
```
