# mysql-commands
#### create a new user that can access database from local or any where
`create user 'riuser'@'%' identified by '@#riuser';`
#### grant permission to new created user
`grant all privileges on *.* to 'riuser'@'%' with grant option;`
