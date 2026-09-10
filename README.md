# Xojo-LiDAR

This is a distance detection system which works on the principle of radar (DAR), and uses light from a laser (Li), and placing the two sections together becomes LiDAR. Low-cost time-of-flight (ToF) LiDAR sensors have opened up practical distance-sensing applications for hobbyists, researchers, and embedded developers.

Here is the screen grab of the running program:

![](https://github.com/eugenedakin/Xojo-LiDAR/blob/main/TF-LunaScreenGrab.png)

To wire up the TF-Luna, here is the wiring diagram:

![](https://github.com/eugenedakin/Xojo-LiDAR/blob/main/LiDARBreadboardRev1.png)


Here are the installation instructions: 
The lgpio library provides low-level hardware access for the Raspberry Pi. It is presumed that a Raspberry Pi 4 B or 5 B is being used with the latest Raspberry Pi OS (Trixie). Open a terminal on Raspberry Pi and type the following commands:

1. sudo apt install swig python3-dev
2. sudo apt install python3-setuptools
3. sudo apt install libunwind8
4. wget https://github.com/joan2937/lg/archive/master.zip
5. unzip master.zip
6. cd lg-master
7. make
8. sudo make install
9. Download Eugene's free lgpio module at: https://github.com/eugenedakin/lgpio-GPIO
10. Download the TF-Luna module at: https://github.com/eugenedakin/lgpio-I2C-TF-Luna
