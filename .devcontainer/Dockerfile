FROM fedora:36

WORKDIR /home

RUN dnf update && \
  dnf -y install gcc gcc-g++ nano wget


RUN useradd -m -G wheel ruby
