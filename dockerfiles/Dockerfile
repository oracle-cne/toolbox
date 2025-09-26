FROM container-registry.oracle.com/os/oraclelinux:8

RUN dnf -y update && \
    dnf install -y bind-utils && \
    dnf install nmap-ncat \
    socat \
    strace \
    tcpdump \
    traceroute \ 
    curl \
    telnet \
    openssl \
    sos \
    nftables \
    iptables \
    ethtool

ENTRYPOINT ["sh"]
