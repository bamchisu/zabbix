zabbix
======

zabbix

這是一個repo 用來紀錄我怎麼使用zabbix監視各種系統/中介軟體的方法，
主要會使用bash/python這些屬於Linux default安裝的語言。

由於彼此的相互依賴關係，必須按照以下的順序進行安裝:
[1] DB: Postgres
[2] php
[3] zabbix server (+agent)
[4] nginx
[5] php-fpm
