FROM alpine:latest
LABEL "maintainer"="arne"
LABEL "repository"="https://github.com/arneee/actions"
LABEL "version"="1.0.1"

LABEL "com.github.actions.name"="SSH"
LABEL "com.github.actions.description"="Run command via SSH"
LABEL "com.github.actions.icon"="server"
LABEL "com.github.actions.color"="orange"

RUN apk update && apk add --no-cache openssh-client

ADD entrypoint.sh /entrypoint.sh


ENTRYPOINT ["/entrypoint.sh"]
