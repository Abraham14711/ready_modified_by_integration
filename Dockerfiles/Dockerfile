from lscr.io/linuxserver/webtop:ubuntu-xfce

run apt-get update -y
run apt-get install -y libgtk-3-dev libxt-dev ocl-icd-opencl-dev libglu1-mesa-dev libvtk9-dev libwxgtk3.2-dev cmake-curses-gui build-essential git
run apt-get install apt-utils -y
run apt-get install qtbase5-dev qtdeclarative5-dev -y

run mkdir Ready && cd Ready && mkdir build && git clone https://github.com/GollyGang/ready.git && cd build && cmake -DCMAKE_BUILD_TYPE=Release ../ready && make

