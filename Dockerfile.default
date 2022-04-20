FROM nginx:alpine

COPY default.conf.template /etc/nginx/templates/
COPY html/ /usr/share/nginx/html/

ENV POD_NAMESPACE="default"

ENV VERSION="1.0"
ENV MESSAGE="Hello OCI DevOps"
ENV BACKGROUND="blue"

ARG CONTEXT_PATH="/webpage"
ENV CONTEXT_PATH=$CONTEXT_PATH
