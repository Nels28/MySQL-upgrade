# MySQL-upgrade
Bash script to upgrade MySQL to MariaDB

A script to upgrade MariaDB from 5.5/10.0/10.1 to 10.2 on CentOS 6 or 7 and intended for use with Plesk Onyx. It also configures /root/.my.cnf with the Plesk admin credentials to ensure standard CentOS logrotate works properly. This has the added benefit of ensuring you can easily run mysqladmin without entering admin DB credentials.

It is integrated with Plesk tools to provide back up, upgrade DBs, and notify Plesk of version changes.
