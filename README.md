# InstallMariadb

reference: https://mariadb.com/kb/en/yum/

curl -sS https://downloads.mariadb.com/MariaDB/mariadb_repo_setup | sudo bash
sudo yum install MariaDB-server galera-4 MariaDB-client MariaDB-shared MariaDB-backup MariaDB-common

systemctl enable mariadb
systemctl start mariadb
mysql_secure_installation

https://cionman.tistory.com/22
