FROM postgres:15.4-alpine3.18
COPY postgresql.conf pg_hba.conf /etc/
CMD ["postgres", "-c", "config_file=/etc/postgresql.conf"]
