#immagine computer hacker

# Partiamo dall'immagine ufficiale di Kathará
FROM kathara/base

# Evitiamo prompt interattivi durante l'installazione
ENV DEBIAN_FRONTEND=noninteractive

# Aggiorniamo i repository e installiamo i pacchetti desiderati
RUN apt-get update
RUN apt-get install -y \
    bridge-utils \
    iproute2 \
    net-tools \

RUN    rm -rf /var/lib/apt/lists/*
