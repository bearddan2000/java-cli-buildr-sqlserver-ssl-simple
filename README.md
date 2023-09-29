# java-cli-buildr-sqlserver-ssl-simple

## Description
A java buildr build, that connects to sqlserver database.

Sql server uses self-signed ssl.

## Tech stack
- java
- buildr
  - 6.8.2

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
