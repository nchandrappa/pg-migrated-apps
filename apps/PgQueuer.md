# PgQueuer

PgQueuer is a Python library leveraging PostgreSQL for efficient job queuing.




[GitHub](https://github.com/janbjorge/PgQueuer)


### Install

```
pip install pgqueuer
```

### Running PqQueuer

Initalize Postgresql

```
python3 -m pgqueuer install --pg-host 172.23.0.1 --pg-port 5432 --pg-user nikhil --pg-database postgres  --pg-password password
```

Initalize YugabyteDB

```
python3 -m pgqueuer install --pg-host 10.151.0.160 --pg-port 5433 --pg-user yugabyte --pg-database yugabyte  --pg-password yugabyte
```

