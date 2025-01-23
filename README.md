# docker-solutions
Various dockerfiles and docker-compose configurations.

## fakturama
Run fakturama on linux and expose the interface through an x server.
The dockerfile is based on the article [Run GUI app in linux docker container on windows host](https://dev.to/darksmile92/run-gui-app-in-linux-docker-container-on-windows-host-4kde).
On a windows host, an x server (like [VcXsrv](https://vcxsrv.com/)) is required.

## paperless-ngx
Run a paperless-ngx instance based on postgres together with pgadmin (based on [docker-compose.postgres-tika.yml](https://github.com/paperless-ngx/paperless-ngx/blob/main/docker/compose/docker-compose.postgres-tika.yml))
The directories for data and media are pointing to the respective subdirectories on the host system.

## postgres
Run a postgres database server with pgadmin.