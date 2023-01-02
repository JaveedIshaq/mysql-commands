# mysql-commands
#### create a new user that can access database from local or any where
`create user 'riuser'@'%' identified by '@#riuser';`
#### grant permission to new created user
`grant all privileges on *.* to 'riuser'@'%' with grant option;`
then run ->
-- mysql> FLUSH PRIVILEGES;
The FLUSH PRIVILEGES statement is used in MySQL to reload the privileges that are stored in the MySQL grant tables in the mysql database. It is typically used after making changes to the user privileges using statements such as GRANT or REVOKE.
