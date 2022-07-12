FROM fedora:36

WORKDIR /home

RUN dnf update && \
  dnf groupinstall -y "Development Tools" "Development Libraries"

RUN useradd -m -G wheel ruby
# after creating image, set user ruby, add su - ruby to /root/.bashrc
