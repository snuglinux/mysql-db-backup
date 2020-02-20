A script for automatically archiving MySQL databases.

The program allows you to automatically back up multiple mysql databases, as well as delete old archive copies.

When mysql-db-backup is executed without parameters, the script reads the configuration file /etc/mysql-db-backup/mysql-db-backup.conf
and searches for all MySQL hosts configuration files with the /etc/mysql-db-backup/hosts directory.

Example host configuration file /etc/mysql-db-backup/hosts/localhost.conf_

To run the script automatically, there is mysql-db-backup.service and the mysql-db-backup.timer timer.

To change the startup time, adjust /usr/lib/systemd/system/mysql-db-backup.timer.d/mysql-db-backup.conf.

The website distribution https://snuglinux.pp.ua
