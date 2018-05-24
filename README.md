# awesome-greenplum
A curated list of awesome Greenplum resources, tools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/kongyew/awesome-greenplum.svg?branch=master)](https://api.travis-ci.org/kongyew/awesome-greenplum.svg?branch=master)

[Greenplum](https://en.wikipedia.org/wiki/Greenplum) is an advanced, fully featured, open source data platform.  It provides powerful and rapid analytics on petabyte scale data volumes.  Uniquely geared toward big data analytics, Greenplum Database is powered by the world’s most advanced cost-based query optimizer delivering high analytical query performance on large data volumes. [Greenplum.org](https://greenplum.org/))

 :elephant: Contributions welcome. Add links through [pull requests](https://github.com/kongyew/awesome-greenplum/pulls) or create an [issue](https://github.com/kongyew/awesome-greenplum/issues) to start a discussion.

## Contents

- [High-Availability](#high-availability)
- [Backups](#backups)
- [GUI](#gui)
- [Distributions](#distributions)
- [CLI](#cli)
- [Server](#server)
- [Monitoring](#monitoring)
- [Extensions](#extensions)
- [Optimization](#optimization)
- [Utilities](#utilities)
- [Language bindings](#language-bindings)
- [Tutorials](#tutorials)
- [Blogs](#blogs)
- [Articles](#articles)
- [Newsletters](#newsletters)
- [PaaS (PostgreSQL as a Service)](#paas-postgresql-as-a-service)
- [Docker images](#docker-images)
- [Videos](#videos)
- [howto](#howto)

### High-Availability
* [PgBouncer](https://pgbouncer.github.io/) - Lightweight connection pooler for PostgreSQL

### Backups
* [gpcrondump](https://gpdb.docs.pivotal.io/530/utility_guide/admin_utilities/gpcrondump.html) - Use gpcrondump to backup databases, data, and objects such as database roles and server configuration files.
* [gpBackup](https://gpdb.docs.pivotal.io/530/utility_guide/admin_utilities/gpbackup.html) - ACreate a Greenplum Database backup for use with the gprestore utility.

### GUI
* [pgAdmin4](https://www.pgadmin.org/) - PostgreSQL Administration and Management GUI.
* [Adminer](https://www.adminer.org/) - Full-featured database management tool written in PHP.
* [OmniDB](https://omnidb.org/en/) - Open Source Collaborative Environment
For Database Management
* [DataGrip](https://www.jetbrains.com/datagrip/) - IDE with advanced tool sets and good cross-platform experience (Commercial Software).
* [DBeaver](https://dbeaver.io) - Universal Database Manager with excellent support for PostgreSQL.


### Distributions
* [Open Source Greenplum - Ubuntu](https://launchpad.net/~greenplum/+archive/ubuntu/db) - The Easiest Way to Get Started with PostgreSQL on Ubuntu.
* [Pivotal Greenplum](https://github.com/mihasic/PostgreSql.Binaries.Lite) - Minimum set of Windows binaries of the PostgreSQL database. Also made available through NuGet.

### CLI
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) - The built-in PostgreSQL CLI client
* [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV

### Extensions]


### Optimization


### Utilities
* [apgdiff](https://www.apgdiff.com/) - Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd's MySQL to PostgreSQL conversion script.
* [ora2pg](http://ora2pg.darold.net) - Perl module to export an Oracle database schema to a PostgreSQL compatible schema.
* [pg\_activity](https://github.com/julmon/pg_activity) - top like application for PostgreSQL server activity monitoring.
* [pg-formatter](https://github.com/gajus/pg-formatter) - A PostgreSQL SQL syntax beautifier (Node.js).
* [pganalyze](https://pganalyze.com) - PostgreSQL Performance Monitoring (Commercial Software).
* [pgbadger](https://github.com/dalibo/pgbadger) - Fast PostgreSQL Log Analyzer.
* [PgBouncer](http://pgbouncer.github.io) - Lightweight connection pooler for PostgreSQL.
* [pgCenter](https://github.com/lesovsky/pgcenter) - Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends.
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) - Export data from PostgreSQL into different data formats.
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way.
* [PGInsight](http://pginsight.io/) - CLI tool to easily dig deep inside your PostgreSQL database.
* [pgloader](https://github.com/dimitri/pgloader) - Loads data into PostgreSQL using the COPY streaming protocol, and does so with separate threads for reading and writing data.
* [pgpool-II](http://www.pgpool.net/mediawiki/index.php/Main_Page) - Middleware that provides connection pooling, replication, load balancing and limiting exceeding connections.
* [pgsync](https://github.com/ankane/pgsync) - Tool to sync PostgreSQL data to your local machine.
* [PGXN client](https://github.com/dvarrazzo/pgxnclient) - Command line tool to interact with the PostgreSQL Extension Network
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics for your PostgreSQL database.
* [PostgREST](https://github.com/PostgREST/postgrest) - Serves a fully RESTful API from any existing PostgreSQL database.
* [pREST](https://github.com/prest/prest) - Serve a RESTful API from any PostgreSQL database (Golang)
* [PostGraphQL](https://github.com/graphile/postgraphile) - A GraphQL schema created by reflection over a PostgreSQL schema.
* [yoke](https://github.com/nanopack/yoke) - PostgreSQL high-availability cluster with auto-failover and automated cluster recovery.
* [pglistend](https://github.com/kabirbaidhya/pglistend) - A lightweight PostgresSQL `LISTEN`/`NOTIFY` daemon built on top of `node-postgres`.
* [ZSON](https://github.com/postgrespro/zson) - PostgreSQL extension for transparent JSONB compression
* [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) - It's a high speed data loading utility for PostgreSQL.
* [pg_migrate](https://github.com/jwdeitch/pg_migrate) - Manage PostgreSQL codebases and make VCS simple.
* [sqitch](https://github.com/theory/sqitch) - Tool for managing versioned schema deployment
* [pgmigrate](https://github.com/yandex/pgmigrate) - CLI tool to evolve schema migrations, developed by Yandex
* [pgcmp](https://github.com/cbbrowne/pgcmp) - Tool to compare database schemas, with capability to accept some persistent differences
* [greenplum-downloader](https://github.com/kongyew/greenplum-downloader) - Tool to download Greenplum files from Pivotal Network
* [greenplum-dockers](https://github.com/kongyew/greenplum-dockers) - Tool to build Greenplum docker files

### Language bindings
* Common Lisp: [Postmodern](https://github.com/marijnh/Postmodern)
* Elixir: [postgrex](https://github.com/elixir-ecto/postgrex)
* Go: [pgx](https://github.com/jackc/pgx)
* Java: [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* .Net/.Net Core: [Npgsql](https://github.com/npgsql/npgsql)
* Node: [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise)
* Perl: [DBD-Pg](http://search.cpan.org/~turnstep/DBD-Pg/Pg.pm)
* PHP: [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Ruby: [pg](https://bitbucket.org/ged/ruby-pg/wiki/Home)
* Rust: [rust-postgresql](https://github.com/sfackler/rust-postgres)

### Tutorials
* [Backup and recover a PostgreSQL DB using gpcrondump](https://greenplum.org/gpdb-sandbox-tutorials/backup-recovery-operations/) - Tutorial about to backup and restore data for Greenplum using gpcrondump.
* [Data loading using gpfdist](https://greenplum.org/gpdb-sandbox-tutorials/data-loading/) - Tutorial about loading data into Greenplum using GpfdistService.
* [Using Greenplum and Apache Spark via JDBC](https://github.com/kongyew/greenplum-spark-jdbc)
* [Using Greenplum-Spark connector](https://github.com/kongyew/greenplum-spark-connector)
* [Using Greenplum and pgAdmin4](https://github.com/kongc-organization/greenplum-pgadmin4)
* [Using Streamsets to load data from Kafka into Greenplum](https://github.com/kongc-organization/greenplum-streamsets)
* [Using Greenplum to access Minio - distributed object storage via S3 Protocol](https://github.com/kongc-organization/greenplum-minio)
*
### Blogs
* [Greenplum.org Blog](https://greenplum.org/blog/) - Blog aggregation service for Greenplum.org.
* [Pivotal Guru blog](https://www.pivotalguru.com/)
* [Pivotal Greenplum blog](https://pivotal.io/pivotal-greenplum)


### Articles
* [Greenplum and Apache Spark via JDBC](http://engineering.pivotal.io/post/getting-started-with-greenplum-spark/)
* [Greenplum and Apache Spark via Greenplum-Spark Connector](https://github.com/kongyew/greenplum-spark-connector)
* [Greenplum and Apache Spark via Greenplum-Spark Connector](http://greenplum-spark-connector.readthedocs.io/en/latest/)
* [Greenplum workload manager](https://greenplum.org/new-era-greenplum-monitoring-workload-management-greenplum-command-center-v4/)

### Newsletters



### Docker images
* [Pivotaldata](https://hub.docker.com/r/pivotaldata/gpdb-base/) - Greenplum official image. Based on the official Greenplum 4.3.7.x.
* [Open source GPDB 5 on Ubuntu](https://hub.docker.com/r/kochanpivotal/gpdb5oss/) - Open Source GPDB 5.x installed on Ubuntu container.
* [postgres](https://hub.docker.com/_/postgres/) -  Official postgres container (from Docker)

### Videos
* [Greenplum Youtube channel](https://www.youtube.com/channel/UCIC2TGO-4xNSAJFCJXlJNwA) - Greenplum related videos
* [PGConf US Youtube channel](https://www.youtube.com/pgconfus/) - Conference videos


### Howto
#### ETL

#### Data Federation


#### Security
* [Security - How to setup Greenplum with Kerberos](https://github.com/kongyew/greenplum-kerberos)
