# MySQL
In this project, I gained expertise in configuring database servers within a primary-replica model.
I effectively implemented a MySQL primary-replica architecture utilizing the two servers designated
by ALX SE School. This setup encompassed the creation of a placeholder database.
Furthermore, I crafted a Bash script to streamline the generation of database backups, thereby
improving the system's efficiency and reliability.

## Project Tasks

* [4-mysql_configuration_primary](./4-mysql_configuration_primary): The MySQL
`my.conf` configuration file used to set up my first server as a primary database
server on the database `tyrell_corp`.

* [4-mysql_configuration_replica](./4-mysql_configuration_replica): The MySQL
`my.conf` configuration file used to set up my second server as the replica
database server on the database `tyrell_corp`.

* [5-mysql_backup](./5-mysql_backup): Bash script that generates a compressed
`tar.gz` archive from a MySQL dump.
  * Usage: `./5-mysql_backup <MySQL root password>`
  * Generates a dump containing all MySQL databases on the root server.
  * Names the resulting tar archive in the format `day-month-year.tar.gz`.
