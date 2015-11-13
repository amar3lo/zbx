#!/bin/bash

/etc/init.d/zabbix-proxy stop

rm -f /var/lib/sqlite/zabbix.db

cp -av /home/zabbix.db /var/lib/sqlite/zabbix.db

chown -R zabbix:zabbix /var/lib/sqlite/

chown -R zabbix:zabbix /var/lib/sqlite/zabbix.db

/etc/init.d/zabbix-proxy start
