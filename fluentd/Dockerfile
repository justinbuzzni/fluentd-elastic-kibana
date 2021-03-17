FROM fluent/fluentd:v1.12.0-debian-1.0

USER root

# RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.0"]
RUN ["gem", "install", "fluent-plugin-grep",  "fluent-plugin-extract_query_params","fluent-plugin-elasticsearch", "fluent-plugin-record-modifier", "--no-document"]

USER fluent