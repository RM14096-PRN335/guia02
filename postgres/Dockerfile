FROM postgres:9.6.3-alpine
ENV POSTGRES_USER='mortal2017'
ENV POSTGRES_PASSWORD='PRN335'
ENV POSTGRES_DB='posts'   

COPY docker-entrypoint.sh /
COPY  post_v2.sql/docker.entrypoint.initdb.d/


ENTRYPOINT ["/docker-entrypoint.sh"]

EXPOSE 5432
CMD ["postgres"]

