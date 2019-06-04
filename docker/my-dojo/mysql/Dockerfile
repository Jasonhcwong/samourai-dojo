FROM      mysql/mysql-server:latest-aarch64

# Copy mysql config
COPY      ./docker/my-dojo/mysql/mysql-dojo.cnf /etc/mysql/conf.d/mysql-dojo.cnf

# Copy content of mysql scripts into /docker-entrypoint-initdb.d
COPY      ./db-scripts/ /docker-entrypoint-initdb.d
