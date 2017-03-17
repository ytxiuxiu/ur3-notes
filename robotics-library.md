```
sudo apt-get install build-essential cmake
sudo apt-get install cmake-curses-gui cmake-gui
```

install bullet
```
sudo apt-get install python2.7-dev

git clone https://github.com/bulletphysics/bullet3.git
cd bullet3
./build_cmake_pybullet_double.sh
cd build_cmake
make
sudo make install
```

install robotics library
```
sudo add-apt-repository ppa:roblib/ppa
sudo apt-get update
sudo apt-get install libboost-dev libcgal-dev libcoin60-dev libdc1394-22-dev libeigen3-dev libqt4-dev libqt4-opengl-dev libode-dev libsimage-dev libsolid-dev libsoqt4-dev libxml2-dev
sudo apt-get install doxygen graphviz
export MAKEFLAGS=-j4

sudo apt-get install librl librl-dev

wget https://github.com/roboticslibrary/rl/archive/0.6.2.tar.gz
tar -xvzf 0.6.2.tar.gz
cd rl-0.6.2
mkdir Release
cd Release
cmake ..
make  // not working...
sudo make install
sudo ldconfig

```
