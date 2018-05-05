#Apache and MariaDB
1) Workspace container, where you enter commands, is the same as the Apache container, so no complex container
interlinking.
2) MariaDB used as a MySQL substitute.
3) Runs in ../www
4) No security, do not use in production.

## To Run
```
sudo docker-compose up -d web database
```