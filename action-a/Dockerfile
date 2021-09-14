FROM debian:9.5-slim

LABEL com.github.actions.icon="activity"
LABEL com.github.actions.color="orange"


ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]

