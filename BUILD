docker build --pull -t libreelec tools/docker/noble

docker run --rm --log-driver none -v `pwd`:/build -w /build -it -e PROJECT=RPi -e DEVICE=RPi5 -e ARCH=aarch64 libreelec make image

#docker run --rm --log-driver none -v `pwd`:/build -w /build -it -e PROJECT=RPi -e DEVICE=RPi4 -e ARCH=aarch64 libreelec scripts/create_addon system-tools
#docker run --rm --log-driver none -v `pwd`:/build -w /build -it -e PROJECT=RPi -e DEVICE=RPi4 -e ARCH=aarch64 libreelec scripts/create_addon network-tools
#docker run --rm --log-driver none -v `pwd`:/build -w /build -it -e PROJECT=RPi -e DEVICE=RPi4 -e ARCH=aarch64 libreelec scripts/create_addon net-snmp
#docker run --rm --log-driver none -v `pwd`:/build -w /build -it -e PROJECT=RPi -e DEVICE=RPi4 -e ARCH=aarch64 libreelec scripts/create_addon docker
