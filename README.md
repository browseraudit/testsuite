# The [BrowserAudit](https://browseraudit.com) test suite

This repository contains an SQL dump of the latest (public) version of the [BrowserAudit](https://browseraudit.com) test suite. Dumps of the `category` and `test` table for the SQL schema are provided.

These dumps can be restored on a PostgreSQL >= 9.3 server using the following command (make sure you back up your database beforehand!):

    pg_restore -h <database_host> -d <database_name> -U <database_user> browseraudit_testsuite_yyyymmdd.sql


