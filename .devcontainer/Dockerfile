FROM fedora:rawhide

WORKDIR /home

RUN dnf -y update && \
  dnf -y install gcc gcc-g++ nano wget git && \
  dnf groupinstall -y "Development Tools" "Development Libraries"

RUN useradd -m -G wheel ruby
# after creating image, set user ruby, add su - ruby to /root/.bashrc
