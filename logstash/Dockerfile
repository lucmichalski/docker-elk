# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.2.2

RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-kv
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
