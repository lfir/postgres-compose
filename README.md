# Docker Compose set-up for Postgres 13 & Pgadmin 4

**Postgres extensions added to the [Base Postgres image](https://github.com/docker-library/postgres/tree/master/13)**
- pgtop
- postgis

#### Notes
- Per user storage dir in Pgadmin: **/var/lib/pgadmin/storage/username**. Used for importing/exporting files.
- Command to view DB resource usage information: docker exec -it containerName su postgres -c pg_top

