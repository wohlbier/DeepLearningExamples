FROM nvcr.io/nvidia/mxnet:19.07-py3
ARG PROXY
ENV http_proxy $PROXY
ENV https_proxy $PROXY
COPY . /workspace/rn50
WORKDIR /workspace/rn50
