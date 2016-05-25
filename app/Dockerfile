FROM ubuntu:16.04

RUN apt-get update && apt-get install -y tcpdump

# UDP Acceptor
EXPOSE 8088/udp

ENTRYPOINT [ "/usr/sbin/tcpdump" ]
