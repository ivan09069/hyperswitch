# docker/fluentd/Dockerfile

FROM fluent/fluentd:v1.19.0-debian
USER root
RUN ["gem",  "install", "fluent-plugin-kafka", "--no-document"]
RUN ["gem",  "install", "fluent-plugin-opensearch", "--no-document"]
USER fluent
