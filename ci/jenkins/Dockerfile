FROM jenkins/inbound-agent:4.7-1-jdk11

USER root
RUN \
    wget -qO- https://github.com/sbt/sbt/releases/download/v1.5.3/sbt-1.5.3.tgz | tar xvz -C /usr/local \
    && ln -s /usr/local/sbt/bin/sbt /usr/local/bin

    USER jenkins