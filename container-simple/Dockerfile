FROM ubuntu:22.04

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y git python3 python3-pip

RUN pip install open-interpreter==0.1.10
RUN pip install numpy matplotlib pandas


# 環境変数の設定
ENV AZURE_API_BASE=https://oai-hands-on.openai.azure.com/ \
    AZURE_API_VERSION=2023-07-01-preview

WORKDIR /root
