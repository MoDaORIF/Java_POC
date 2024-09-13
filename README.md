#

## MariaDB init (arch-based)
`sudo pacman -S mariadb`
`sudo mariadb-install-db --user=MySQL --basedir=/usr --datadir=/var/lib/mariadb`
`sudo systemctl start mariadb`
`sudo mariadb-admin -u root password [YOUR_PASSWORD]`
`mariadb -u root -p`
`[mariadb] # create database springbootdb;`
