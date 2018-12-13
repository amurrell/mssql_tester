# MSSQL TESTER

```
docker pull mcr.microsoft.com/mssql/server:2017-latest
```

then start it up,

```
./mssql-up
```

or, if you are using proxylocal for network (with DockerLocal containers) do

```
./mssql-up-proxylocal
```

## Connect from your host machine using:

- host: 0.0.0.0
- user: SA
- pass: MSD0ck3r!
- port: 1433
- db: master

## Connect from a DockerLocal container (w/ ProxyLocal)

- host: ms-docker
- user: SA
- pass: MSD0ck3r!
- port: 1433
- db: master


## Limits

Currently does not persist data!