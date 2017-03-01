# Scripts used for installing, configuring or repairing.

Mainly used on Mac OS.

## Contents
### Postgres
Due to a bug when restarting Postgres, it sometimes cannot start the process
again - because a PID-file already exists. This script holds the routine for
fixing this, found the solution
[here](http://www.innovaedge.com/2015/08/08/fixing-postgres-that-doesnt-come-up-on-macosx-after-a-restart/).
