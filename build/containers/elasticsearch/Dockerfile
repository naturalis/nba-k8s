FROM docker.elastic.co/elasticsearch/elasticsearch:{{elasticsearch_version}}
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin remove --purge x-pack
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch \
    repository-s3
