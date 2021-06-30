# openocd_RPI4
openocd configuration for Raspberry PI 4
to work with ATSAMD21E18 or higher

openocd installation steps:
- sudo apt update
- sudo apt upgrade
- git clone http://openocd.zylin.com/openocd
- cd openocd/
- sudo apt install libtool
- ./bootstrap
- ./configure --enable-sysfsgpio --enable-bcm2835gpio
- make
- sudo make install
