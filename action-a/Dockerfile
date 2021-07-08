FROM debian:9.5-slim
ADD entrypoint.sh /entrypoint.sh
RUN git update-index --chmod=+x action-a/entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
