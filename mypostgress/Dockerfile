FROM postgres:9.5

Run apt-get update
				

COPY init-db.sql /docker-entrypoint-initdb.d/

VOLUME dbdata:/var/lib/postgressql/data


