FROM overv/openstreetmap-tile-server

RUN deluser renderer
#RUN adduser --disabled-password --gecos "" renderer

# Start running
COPY run.sh /
ENTRYPOINT ["/run.sh"]
CMD []
EXPOSE 80 5432
