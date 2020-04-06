---
title: 'MySQL compatibility'
category: 'reference'
---

# MySQL compatibility

This document contains information about the compatibility of PlanetScaleDB with MySQL features.

While Vitess [supports running instances of MariaDB](https://vitess.io/docs/get-started/local/), PlanetScaleDB currently does not.

## PlanetScaleDB supports all core MySQL features

PlanetScaleDB supports all core features of MySQL 5.7, including standard SQL statements and MySQL-specific commands. In general, you can issue queries against your database as if it were a MySQL database.

## Limitations

PlanetScaleDB uses [Vitess](https://vitess.io) to scale your database. This means that the PlanetScaleDB only supports the same set of MySQL features as the latest version of Vitess.

To learn about what MySQL features Vitess supports, see [the Vitess documentation](https://vitess.io/docs/reference/mysql-compatibility/).
