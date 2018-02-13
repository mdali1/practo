FROM ubuntu
RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y net-tools
RUN apt-get install -y openssh-server
RUN useradd gamut -m -d /home/gamut -s /bin/bash
RUN apt-get install -y sudo
ENTRYPOINT service ssh restart &bash
