# fluentd/Dockerfile

FROM fluent/fluentd:v1.12.0-debian-1.0
USER root
COPY /home/kalana/apps/jboss-4.2.3.GA/server/G9/log/server.log /fluentd/log
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.3"]
USER fluent
