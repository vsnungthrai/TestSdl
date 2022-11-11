FROM ubuntu:latest

RUN apt update && DEBIAN_FRONTEND=noninteractive
RUN apt-get install gcc -y
RUN apt-get install libsdl2-dev -y
RUN apt-get install libsdl2-ttf-dev -y
RUN apt-get install libsdl2-image-dev -y
RUN apt-get install libsdl2-mixer-dev -y
RUN apt-get install sudo -y
RUN apt-get install make -y
RUN apt-get install git -y
RUN apt-get install vim -y
RUN apt-get install nano -y
RUN git clone https://github.com/vsnungthrai/TestSdl.git
RUN chmod -R 777 TestSdl
ENV DISPLAY=host.docker.internal:0.0
