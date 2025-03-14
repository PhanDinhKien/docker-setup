# Use the official Kibana image as the base
FROM docker.elastic.co/kibana/kibana:8.6.0

# Set environment variables
ENV ELASTICSEARCH_HOSTS=http://localhost:9200

# Expose Kibana port
EXPOSE 5601

# Start Kibana
CMD ["/bin/tini", "--", "/usr/share/kibana/bin/kibana"]
