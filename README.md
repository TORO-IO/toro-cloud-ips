# Public IP Addresses of TORO Cloud in a Security Group

AWS CloudFormation templates used to create a security group with a list of all public IPs of TORO Cloud. These
CloudFormation templates whitelist all Public IP Addresses associated to TORO Cloud infrastructure. The CloudFormation
templates are specific to what ports you'd like to whitelist. Currently we support the following:

Application | Port(s) Whitelisted | Template Name
--- | --- | ---
MySQL/Amazon Aurora | 3306 | toro-cloud-mysql-security-group.json
Microsoft SQL | 1433 | toro-cloud-mssql-security-group.json
OracleDb | 3306 | toro-cloud-oracledb-security-group.json
PostgreSQL | 5432 | toro-cloud-postgresql-security-group.json

Whenever there are changes with our public IPs, we update these templates as well for the ease of all users.

## Errors with the templates?
Find support portal on http://support.torocloud.com/
