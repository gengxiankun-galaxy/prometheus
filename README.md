PROMETHEUS
=========

通过 ansible 构建 prometheus 监控方案

Installation
------------

`ansible-galaxy install gengxiankun.prometheus`

Role Variables
--------------

parameter | description
------------ | -------------
OPT_PATH | 部署目录

Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.prometheus

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
