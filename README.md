# groovy-cli-gradle-sqlserver-ssl-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

Sql server uses self-signed ssl.

## Tech stack
- groovy
- gradle
  - hibernate
  - hql
  - log4j
  - sqlserver driver

## Docker stack
- alpine:edge
- gradle:jdk11
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
