FROM rust:latest

# 必要なパッケージのインストール
RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
        git \
        pkg-config \
        build-essential \
        clang \
        lldb \
        cmake \
        libssl-dev \
        qemu-system \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace


