# scala-web-sbt-spring-jsp-cockroachdb-single-node-without-ssl-simple

## Description
A jsp springboot scala sbt build,
that connects to cockroach database.

A scala sbt build, that connects to single node
cockroach database without ssl.

## Tech stack
- springboot
  - jsp
- sbt
  - postgres drivers
  - lombok
- bootstrap
- jquery
- dataTable

## Docker stack
- cockroachdb/cockroach:v19.2.2
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
