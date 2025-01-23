# docker-solutions
Various dockerfiles and docker-compose configurations.

## fakturama
Run fakturama on linux and expose the interface through an x server.
The dockerfile is based on the article [Run GUI app in linux docker container on windows host](https://dev.to/darksmile92/run-gui-app-in-linux-docker-container-on-windows-host-4kde).
On a windows host, an x server (like [VcXsrv](https://vcxsrv.com/)) is required.

## postgres
Run a postgres database server with pgadmin.