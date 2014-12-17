安裝在LNPP環境中，除OS外全部Source Install，也就是說從Source Code安裝加設定

Linux OS:	Linux Mint (Base on Ubuntu)
Web: 		Nginx
DB:		Postgres
PHP:		php-fpm on Nginx

由於彼此的相互依賴關係，必須按照以下的順序進行安裝:
[1] DB: Postgres
[2] php
[3] zabbix server (+agent)
[4] nginx
[5] php-fpm
