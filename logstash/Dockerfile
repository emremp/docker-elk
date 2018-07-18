# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:6.3.0
RUN logstash-plugin install logstash-input-http
RUN logstash-plugin install logstash-filter-json

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
