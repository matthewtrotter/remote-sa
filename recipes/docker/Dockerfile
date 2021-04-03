FROM ubuntu:20.04

# RUN add-apt-repository ppa:gnuradio/gnuradio-releases
RUN apt update
RUN apt install -y tzdata
RUN apt install -y software-properties-common python3-gi gobject-introspection gir1.2-gtk-3.0
RUN add-apt-repository -y ppa:gnuradio/gnuradio-releases
RUN apt update
RUN apt install -y gnuradio/focal
