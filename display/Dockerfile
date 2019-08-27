FROM balenalib/raspberrypi3-ubuntu

RUN install_packages cec-utils -y

COPY display/scripts /usr/src/

RUN chmod +x /usr/src/*.sh

CMD /usr/src/start.sh