# Rduino
Small library providing Arduino-like API for some of Raspberry Pi 4 peripherals on Linux system.

![GitHub release](https://img.shields.io/github/v/release/RPatelski/Rduino)
![GitHub issues](https://img.shields.io/github/issues/RPatelski/Rduino)
![GitHub](https://img.shields.io/github/license/RPatelski/Rduino)

## Modules
Currently API for only few peripherals is prepared
- GPIO
- SPI

## How to use
Library is delivered with `CMakeLists.txt` ready to compile and install the library.
```Shell
mkdir bin
cd bin
cmake ..
make
```
After copilation `sudo make install` installs the library to /usr/local/ for easy linking.

To compile include `rduino.h` and link agains `rduino` by `-lrduino` flag.
