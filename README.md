Ora11HRdb
=========

Oracle 11 db hr database


* Download XE 11 database [http://www.oracle.com/technetwork/database/database-technologies/express-edition/overview/index.html]
* Learn to Use Oracle Database 11g Express Edition - Part 1  [https://apex.oracle.com/pls/otn/f?p=44785:24:101998711145653:::24:P24_CONTENT_ID,P24_PROD_SECTION_GRP_ID,P24_PREV_PAGE:5813,,24]
* Other docs [http://docs.oracle.com/cd/E17781_01/index.htm]
* about xe 11g [http://docs.oracle.com/cd/E17781_01/admin.112/e18585/toc.htm]
 

##Installing the HR Schema

All scripts necessary to create the Human Resource (HR) schema reside in $ORACLE_HOME/demo/schema/human_resources.

You need to call only one script, hr_main.sql, to create all the objects and load the data. The following steps provide a summary of the installation process:

    Log on to SQL*Plus as SYS and connect using the AS SYSDBA privilege.

    ```sql
    sqlplus connect sys as sysdba
    Enter password: password
    ```

    To run the hr_main.sql script, use the following command:

    ```sql
    SQL> @?/demo/schema/human_resources/hr_main.sql
    ```

    Enter a secure password for HR

    specify password for HR as parameter 1:
    Enter value for 1:
    ...
