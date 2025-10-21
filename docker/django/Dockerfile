#FROM registry.redhat.io/ubi8/python-39:latest
FROM registry.redhat.io/ubi9/python-312

ADD ./app . 
RUN pip install -r requirements.txt

ENTRYPOINT /bin/bash docker-entrypoint.sh
