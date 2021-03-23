FROM golang:1.15.10

RUN apt-get update -y -qq \
    && apt-get install -y -qq python3 python3-pip python3-venv \
    && apt-get install -y -qq libpcap-dev \
    && rm -rf /var/lib/apt/lists/*
