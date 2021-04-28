FROM ubuntu:20.04

RUN apt-get update -qq -y
RUN apt-get install -y \
    git \
    curl

RUN curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 \
    && chmod 700 get_helm.sh \
    && ./get_helm.sh \
    && rm ./get_helm.sh

