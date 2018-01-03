FROM elasticsearch:5

RUN touch /usr/share/elasticsearch/config/elasticsearch.yml && \
    echo "cluster.name: 'docker-cluster'\nnetwork.host: 0.0.0.0\ndiscovery.zen.minimum_master_nodes: 1" > /usr/share/elasticsearch/config/elasticsearch.yml
