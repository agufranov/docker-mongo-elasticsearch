FROM python

RUN pip install mongo-connector

CMD ["mongo-connector", "-m", "mongo:27017", "-t", "elasticsearch:9200", "-d", "elastic_doc_manager", "-n", "paradigm1.users,paradigm1_studies.studies"]
