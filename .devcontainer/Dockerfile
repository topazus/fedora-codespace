FROM fedora:rawhide

WORKDIR /home

RUN dnf -y update && \
  dnf -y install gcc gcc-c++ nano wget git
  # dnf -y install go2rpm go-vendor-tools

RUN useradd -m -G wheel ruby
# after creating image, set user ruby, add su - ruby to /root/.bashrc
