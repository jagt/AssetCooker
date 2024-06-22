## Json2Db

Proof of concept JSON to Sqlite3.

Eventually need a way to merge multiple sqlite3 databases in final and query across multiples as 1.

Need sqlite-utils:


```
pip install sqlite-utils sqlean.py sqlite-dump
```

For query across multiple dbs:

* <https://sqlite-utils.datasette.io/en/stable/cli.html#attaching-additional-databases>
* <https://www.sqlite.org/swarmvtab.html>
* <https://sqlite.org/src/doc/tip/ext/misc/unionvtab.c>

