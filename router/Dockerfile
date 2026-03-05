#immagine computer hacker

# Partiamo dall'immagine ufficiale di Kathará
FROM kathara/base

# Evitiamo prompt interattivi durante l'installazione
ENV DEBIAN_FRONTEND=noninteractive

# Aggiorniamo i repository e installiamo i pacchetti desiderati
RUN apt-get update
RUN apt-get install -y \
    nmap \
    iperf3 \
    python3 \
    python3-pip \
    tcpdump \
    pipx
RUN    rm -rf /var/lib/apt/lists/*
RUN    pipx install scapy
