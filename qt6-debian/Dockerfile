
FROM debian:bookworm

WORKDIR /opt

RUN apt update
RUN apt install qt6-base-dev -y
RUN apt install gcc -y && apt install g++ -y
RUN apt install make -y
RUN apt install mc -y

RUN ln -s /usr/lib/qt6/bin/qmake6 /usr/bin/qmake
RUN apt-get install libboost-all-dev -y
