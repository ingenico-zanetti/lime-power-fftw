# lime\_power\_fftw

`lime_power_fftw` is a program that obtains a power spectrum from LimeSDR
devices using the FFTW library to do FFT.

It is cloned from rtl-power-fftw.

## Prerequisites

In order to prepare your environment to build from the sources you have to first install a couple of development libraries.
This step is needed only the first time.

    sudo apt-get install libfftw3-dev libtclap-dev

## Installation

To compile the program, cd into the directory where you have cloned the code
and do:

    mkdir build
    cd build
    cmake ..
    make

This should make the `lime_power_fftw` binary in the build directory.
If you copy it into a directory in your `PATH`, you can call it from everywhere.
You can also do `make install` and by default it will be copied to `/usr/local/bin`.

## Documentation

The man page of `lime_power_fftw` is available [here](doc/lime_power_fftw.1.md).
It is maintained in Markdown format suitable for reading online, but it is
also converted into a regular man page that gets installed along with the
program.

## TODO:

  - ... (there's always something, isn't it?!)

