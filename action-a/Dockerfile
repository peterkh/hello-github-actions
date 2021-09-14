FROM debian:9.5-slim

LABEL com.github.actions.icon="activity"
LABEL com.github.actions.color="orange"
LABEL com.github.actions.name="The name of your GitHub Action"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]

