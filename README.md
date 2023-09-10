# Test Oracle DB instance

sqlplus system/mysecurepassword@localhost:1521/XEPDB1

## To install the sample customers/orders DB, do the following:
1. Connect to the docker container via Docker Desktop.

2. Change to the sample-db directory and connect to the XEPDB1 DB:
    ```bash
    cd /sample-db
    sqlplus system/mysecurepassword@localhost:1421/XE
    ```

3. Run the install script for the customers/orders sample DB:
    ```sql
    sql> @co_install.sql
    ```
