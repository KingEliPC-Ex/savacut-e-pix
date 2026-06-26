FROM debian:12-slim

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt install -y \
    sudo \
    wget \
    curl \
    nano \
    iputils-ping \
    ca-certificates \
    git \
    bash-completion

CMD ["bash"]
