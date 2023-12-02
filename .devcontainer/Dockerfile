FROM mcr.microsoft.com/devcontainers/base:bookworm

RUN apt-get update

# basics
RUN apt-get install --no-install-suggests -y wget bash-completion build-essential

# qemu build deps
RUN apt-get install --no-install-suggests -y python3 python3-pip flex bison

# qemu deps
RUN apt-get install --no-install-suggests -y git libglib2.0-dev libfdt-dev libpixman-1-dev zlib1g-dev ninja-build

# qemu optional deps
RUN apt-get install --no-install-suggests -y libsdl2-dev libgtk-3-dev libvte-dev libcapstone-dev libnfs-dev libiscsi-dev libaio-dev libbluetooth-dev libcapstone-dev libbrlapi-dev libbz2-dev libcap-ng-dev libcurl4-gnutls-dev libgtk-3-dev libibverbs-dev libjpeg62-turbo-dev libncurses5-dev libnuma-dev librbd-dev librdmacm-dev libsasl2-dev libsdl2-dev libseccomp-dev libsnappy-dev libssh-dev libvde-dev libvdeplug-dev libvte-2.91-dev libxen-dev liblzo2-dev valgrind xfslibs-dev
