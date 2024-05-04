## Create a Database config file in the application servers 
vi dbinfo.inc

## Copy and Past the Below Data in the file after updating
```bash
<?php

define('DB_SERVER', 'prod-database.c3wsmu6gu78x.us-west-1.rds.amazonaws.com');
define('DB_USERNAME', 'admin');
define('DB_PASSWORD', 'admin12345');
define('DB_DATABASE', 'phpappdatabase');

?>
```
