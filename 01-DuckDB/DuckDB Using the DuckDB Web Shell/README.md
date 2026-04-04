# DuckDB Using the DuckDB Web Shell

You can use the DuckDB Web Shell directly in your browser at https://shell.duckdb.org/

<img src="image\DuckDB Web Shell.png" width="100%" height="40%">

Enter the .help command

```sh
.help
```

<img src="image\help.png" width="100%" height="40%">

Enter the .examples command

```sh
.examples
```

<img src="image\examples.png" width="100%" height="40%">

Enter the SELECT count(*) FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/lineitem.parquet'; command

```sh
SELECT count(*) FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/lineitem.parquet';
```

<img src="image\count().png" width="100%" height="40%">

Enter the SELECT * FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/lineitem.parquet' limit 10; command

```sh
SELECT * FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/lineitem.parquet' limit 10;
```

<img src="image\limit 10.png" width="100%" height="40%">

Enter the SELECT avg(l_extendedprice) FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/lineitem.parquet'; command

```sh
SELECT avg(l_extendedprice) FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/lineitem.parquet';
 ```

<img src="image\avg(l_extendedprice).png" width="100%" height="40%">

Enter the SELECT n_name, count(*)
FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/customer.parquet',
     'https://shell.duckdb.org/data/tpch/0_01/parquet/nation.parquet'
WHERE c_nationkey = n_nationkey GROUP BY n_name; command

```sh
SELECT n_name, count(*)
FROM 'https://shell.duckdb.org/data/tpch/0_01/parquet/customer.parquet',
     'https://shell.duckdb.org/data/tpch/0_01/parquet/nation.parquet'
WHERE c_nationkey = n_nationkey GROUP BY n_name;

 ```

<img src="image\Join.png" width="100%" height="40%">

---