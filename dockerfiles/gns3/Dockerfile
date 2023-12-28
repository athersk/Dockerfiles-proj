FROM ubuntu:20.04

LABEL Version=1.0
LABEL Author=Ather
LABEL Email=atherking@gmail.com


RUN apt-get update && \
    apt-get install -y software-properties-common && \
    rm -rf /var/lib/apt/lists/* && \

    add-apt-repository ppa:gns3/ppa  && \

    apt install -y gns3-gui gns3-server && \
    
    rm -rf /var/lib/apt/lists/*  && \
    apt clean

WORKDIR /home/ather/gns


