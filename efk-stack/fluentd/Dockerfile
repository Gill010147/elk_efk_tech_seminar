FROM fluent/fluentd:v1.16-1
USER root
RUN apk add --no-cache bash curl
RUN gem install fluent-plugin-elasticsearch
USER fluent