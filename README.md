# network-ball-gtk

Display network speed and memory information on linux desktop platform.
Similar to QiHu360 balls.


## How to run?
download binary file `network-ball-gtk` from .
```
wget xxx
```
give executable permissions
```
chmod +x network-ball-gtk
```

## Auto startup
find the boot self-starting management software in your system. add it.
*Note: if a black background appears, please add `sleep 20` before run it, to wait your system start up*

## How to build?
Install cmake && gtk3+, 

Example, In Linux Mint 19:
```
apt install libgtk-3-dev
apt install cmake
```
> Notic: may you need change the cmake version in CMakeLists.txt file

build it
```
cmake .
make
```

Thanks deepin-system-monitor.
https://github.com/manateelazycat/deepin-system-monitor

![](https://github.com/AloneBo/gtk-netspeed-popup/blob/master/linuxnetspeedpopup.png?raw=true)