Actually the debian distro is Bookworm.

This image is useful if you want to compile, build, run and test codes written in C/C++ with support for Qt6 (obviously only QtCore) version 6.4.2 and also with support for boost libraries (1.74.0.3).

You can use both qmake and qmake6 as commands to run qmake to generate the Makefile based on the .pro file, and then you can easily use the make command to compile the code.

To make it easy, mc (Midnight Commander) is already installed.

You can find this image at this link: 

https://hub.docker.com/r/bamundo/qt6-debian

Or, if you prefer, you can directly pull the image by using the command: 

docker pull bamundo/qt6-debian

If you want to use this simple Dockerfile directly, copy the file into a your directory and then execute the following command:

docker image build -t <imageName> <DockerfilePath>

