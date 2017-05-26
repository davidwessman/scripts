# Scripts used for installing, configuring or repairing.

Mainly used on Mac OS.

## Contents
### Postgres
Due to a bug when restarting Postgres, it sometimes cannot start the process
again - because a PID-file already exists. This script holds the routine for
fixing this, found the solution
[here](http://www.innovaedge.com/2015/08/08/fixing-postgres-that-doesnt-come-up-on-macosx-after-a-restart/).

### Find process of port 3000
Sometimes when closing rails in a bad way, it holds port 3000.

This scripts lists the PIDs holding the port.

### Docker-Valgrind
Valgrind doesn't run well on Mac OS, so Docker is used to create an
ubuntu-environment.

### Setup valgrind
This prepares the docker-valgrind setup to be able debug memory leaks.
