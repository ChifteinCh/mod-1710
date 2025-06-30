FROM eclipse-temurin:8-jdk

# Установка 32-битных библиотек
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    libc6:i386 \
    libncurses5:i386 \
    libstdc++6:i386 \
    zlib1g:i386 && \
    rm -rf /var/lib/apt/lists/*