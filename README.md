# ansible-role-zabbix
一个用于批量部署zabbix-agent的ansible-role
Ansible 版本为2+， role支持Centos6/7，zabbix-agent支持3.0.2

## 配置
清单文件'hosts'应配置
```
[zabbix]
192.168.123.168
```

##
执行
```bash
ansible-playbook -i hosts site.yml
```
