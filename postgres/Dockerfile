FROM postgres:latest

COPY create_table.sql /docker-entrypoint-initdb.d/

# The PostgreSQL Docker image has a special behavior where 
# any .sql, .sql.gz, or .sh files placed in this directory will 
# be executed automatically when the container is initialized.