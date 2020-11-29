# OSWA - INVENTORY

## INSTALLATION

### MySQL database

```
$ mysql -uroot

mysql> CREATE DATABASE <DB_NAME>
mysql> exit

$ mysql -uroot <DB_NAME> < inventory.sql

```

### Config

```
# /includes/config.php

define( 'DB_HOST', 'localhost' );    // Set database host
define( 'DB_USER', 'root' );         // Set database user
define( 'DB_PASS', '' );             // Set database password
define( 'DB_NAME', '<DB_NAME>' );    // Set database name
```

### Roles

###### Administrator

```
User: admin
Password: admin
```

###### Special

```
User: special
Password: special
```

###### Default User

```
User: user
Password: user
```
