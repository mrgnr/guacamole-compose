# Docker Compose for Guacamole

Run [Apache Guacamole][guacamole] using [Docker Compose][docker-compose].

## Running

Run the setup script:

```
$ ./setup.sh
```

Run the stack using Docker Compose:

```
$ docker-compose up
```

Once all services are up, you can visit http://localhost:8080/guacamole in your browser.
The default username and password are both `guacadmin`.

[docker-compose]: https://docs.docker.com/compose/
[guacamole]: https://guacamole.apache.org/
