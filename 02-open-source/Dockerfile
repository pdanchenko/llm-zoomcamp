FROM ubuntu:latest
LABEL authors="pdanchenko"

ENTRYPOINT ["top", "-b"]

FROM ollama/ollama
COPY ./ollama_files/ /root/.ollama/
