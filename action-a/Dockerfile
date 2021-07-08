FROM debian:9.5-slim
ADD entrypoint.sh /entrypoint.sh
COPY . /src
RUN chmod+x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
