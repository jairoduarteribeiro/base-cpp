FROM jairoduarteribeiro/llvm-cmake-ninja:0.0.5

RUN set -eux; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
        vim; \
    rm -rf /var/lib/apt/lists/*

USER dev
