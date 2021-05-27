FROM gameservers/steamcmd
USER root
RUN apt update \
    && dpkg --add-architecture i386 \
    && apt-get install -y software-properties-common apt-transport-https wine-stable xvfb

