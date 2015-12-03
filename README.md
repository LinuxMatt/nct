nct
===

New Colored Tetris

[![Build Status](https://travis-ci.org/LinuxMatt/nct.svg?branch=master)](https://travis-ci.org/LinuxMatt/nct)


Build dependencies
------------------
You will need the 'GNU toolchain' to build the project (gcc, make, autotools...).

On Ubuntu, you can run the following commands to install all requirements:
- sudo apt-get install dh-make
- sudo apt-get install intltool
- sudo apt-get install build-essential
- sudo apt-get install libncurses5-dev

Compiling
---------
First, you should install the build dependencies.
Then, from the top directory, run:
./autogen.sh && make

Supported systems
-----------------
- Ubuntu 14.04 LTS
- Solaris
- ...
