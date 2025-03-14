# Use the official Elasticsearch image
FROM docker.elastic.co/elasticsearch/elasticsearch:8.6.0

# Set environment variables for Elasticsearch
ENV discovery.type=single-node
ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"

# Expose the default Elasticsearch ports
EXPOSE 9200 9300

# Set permissions for Elasticsearch data directory
RUN mkdir -p /usr/share/elasticsearch/data

# Start Elasticsearch
CMD ["/usr/share/elasticsearch/bin/elasticsearch"]