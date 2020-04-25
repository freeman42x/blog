# Haskell database access libraries

Connect to any database:

* [beam-core](https://hackage.haskell.org/package/beam-core)
* [HDBC](https://hackage.haskell.org/package/HDBC) - [tutorial](http://book.realworldhaskell.org/read/using-databases.html)
* [HDBC-odbc](https://hackage.haskell.org/package/HDBC-odbc)
* [persistent](https://hackage.haskell.org/package/persistent)
* [esqueleto](https://hackage.haskell.org/package/esqueleto) - [tutorial](https://www.schoolofhaskell.com/school/starting-with-haskell/li[](braries-and-frameworks/persistent-db)
* [hsql](https://hackage.haskell.org/package/hsql) - [tutorial](https://passingcuriosity.com/2008/accessing-sql-databases-with-haskell-hsql/)
* [groundhog](https://hackage.haskell.org/package/groundhog)
* [selda](https://hackage.haskell.org/package/selda)
* [data-basic](https://hackage.haskell.org/package/data-basic)
* [relational-record](https://hackage.haskell.org/package/relational-record)
* [project-m36](https://hackage.haskell.org/package/project-m36)

MS SQL Server:

* [odbc](https://hackage.haskell.org/package/odbc) - Haskell binding to the ODBC API, aimed at SQL Server driver
* [mssql-simple](https://hackage.haskell.org/package/mssql-simple)

PostgreSQL:

* [opaleye](https://hackage.haskell.org/package/opaleye)
  * [rel8](https://github.com/ocharles/rel8)
  * [tisch](https://github.com/k0001/tisch)
  * [girella](https://github.com/silkapp/girella)
* [hasql](https://hackage.haskell.org/package/hasql) - for PostgreSQL
* [postgresql-simple](https://hackage.haskell.org/package/postgresql-simple)
* [postgresql-query](https://hackage.haskell.org/package/postgresql-query)
* [postgresql-transactional](https://hackage.haskell.org/package/postgresql-transactional)
* [squeal-postgresql](https://hackage.haskell.org/package/squeal-postgresql)
* [postgresql-orm](https://hackage.haskell.org/package/postgresql-orm)
* [postgresql-typed](https://hackage.haskell.org/package/postgresql-typed)

MySQL:

* [mysql-simple](https://hackage.haskell.org/package/mysql-simple)

Optimal is one of:

* ✔ [beam-core](https://hackage.haskell.org/package/beam-core) for reasons, see: [How does beam compare with <x>?](https://tathougies.github.io/beam/about/faq/#how-does-beam-compare-with-x)
* Persistent + Esqueleto
* [odbc](https://hackage.haskell.org/package/odbc) - Haskell binding to the ODBC API, aimed at SQL Server driver