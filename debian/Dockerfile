FROM debian:bullseye

RUN apt-get -yqq update && \
    apt-get -yqq install jq curl unzip && \
    curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
    unzip awscliv2.zip && \
    ./aws/install
