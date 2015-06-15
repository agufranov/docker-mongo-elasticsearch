FROM elasticsearch

RUN /usr/share/elasticsearch/bin/plugin --install jettro/elasticsearch-gui

COPY ./elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

CMD ["elasticsearch"]
