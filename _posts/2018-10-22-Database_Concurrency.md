---
title: "Database concurrency (with MS SQL Server)"
tags: [Database, SQL]
---

Some links about managing concurrent database read/updates:
* https://www.red-gate.com/simple-talk/sql/t-sql-programming/developing-modifications-that-survive-concurrency/
* https://stackoverflow.com/questions/7843733/confused-about-updlock-holdlock
* https://sqlperformance.com/2014/07/t-sql-queries/isolation-levels

Using an update which returns results (MS SQL Server):
* https://stackoverflow.com/questions/3860975/sql-update-top1-row-query/37799974#37799974
* https://docs.microsoft.com/en-us/sql/t-sql/queries/output-clause-transact-sql?view=sql-server-2017

Specific to pyodbc:
* https://github.com/mkleehammer/pyodbc/wiki/Database-Transaction-Management

And... connection pooling:
* https://blog.pythian.com/sql-server-understanding-and-controlling-connection/

Bonus links: 
* Efficient random row selection: https://stackoverflow.com/questions/19412/how-to-request-a-random-row-in-sql
* Inserting multiple rows efficiently: 
   * https://stackoverflow.com/questions/8134602/psycopg2-insert-multiple-rows-with-one-query
   * http://initd.org/psycopg/docs/extras.html#fast-exec
