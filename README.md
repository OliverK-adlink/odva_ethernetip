odva_ethernetip [![Build Status](https://travis-ci.org/ros-drivers/odva_ethernetip.svg?branch=indigo-devel)](https://travis-ci.org/ros-drivers/odva_ethernetip)
===============

This repo contains a ROS-ready library which implements EtherNet/IP (Industrial Protocol).

Please find more information on the ROS Wiki:

http://wiki.ros.org/odva_ethernetip (coming soon)


Build steps:
1. install dep. 
  * apt install catkin libboost-all-dev
  * manual install console_bridge
    * git clone https://github.com/ros/console_bridge
    * mkdir build; cd build
    * cmake -DCMAKE_INSTALL_PREFIX=../install ../console_bridge
    * make install
    * export CMAKE_PREFIX_PATH=~/install/
  
